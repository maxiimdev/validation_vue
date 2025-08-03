# Form Validation

A Vue 3 application featuring a form with input validation, phone number masking, and password confirmation. Built with Vuelidate, VueUse/Maska, and SCSS for a responsive UI.

## Description

A simple form for collecting user data (name, email, phone, message, password) with real-time validation, internationalized error messages, and a phone number mask. Includes a checkbox for terms agreement and a submit button with loading state.

## Features

-- Form Fields: Name, Email, Phone (with mask), Message, Password, Confirm Password, Terms Checkbox.

-- Validation: Real-time validation using Vuelidate with i18n error messages.

-- Phone Mask: Formats phone input as +7 (###) - ### - ## - ## via VueUse/Maska.

-- Loading State: Submit button shows loading animation during mock API call.

-- Form Reset: Clears all fields after successful submission.

## Tech Stack

-- Vue 3: Composition API: setup() for component structure.

-- Vuelidate: Form validation with custom validators.

-- VueUse/Maska: Phone number input masking.

-- SCSS: Custom styles with responsive design.

-- Vite: Build tool and dev server.
