# AI-Powered Public Forum for Problem-Solving

## Overview

This project aims to create a platform where users can upload their problems, and an AI system will automatically categorize and organize them into suitable topics. The public forum allows users to view and discuss these problems, while a companion mobile app enables users to interact with the content by swiping right to save and left to not see such types of problems.

## Features

### Web Platform

1. **User Authentication:**
   - Users should be able to create accounts and log in securely.
   - Use OAuth or other secure authentication methods.

2. **Problem Submission:**
   - Users can submit problems through a user-friendly form.
   - Include fields such as problem description, tags, and optional attachments.

3. **AI Categorization:**
   - Implement an AI system to automatically categorize problems based on their content.
   - Utilize natural language processing (NLP) techniques to understand and classify problems into relevant topics.

4. **Public Forum:**
   - Display a public forum where categorized problems are listed.
   - Users can browse and search for problems based on categories and tags.

5. **Discussion Threads:**
   - Each problem should have a dedicated discussion thread.
   - Users can comment on and discuss the problems.

### Mobile App

1. **Authentication and Sync:**
   - Users can log in with the same credentials as the web platform.
   - Sync user data seamlessly between the web and mobile platforms.

2. **Swipe Interaction:**
   - Implement a swipe-based interface for user interaction.
   - Swipe right to save a problem for later reference.
   - Swipe left to choose not to see it again.

3. **Saved Problems:**
   - Users can access a list of problems they have saved.
   - Include features to unsave problems and manage the saved list.

4. **Reported Problems:**
   - Users can view a list of problems they have reported.
   - Include a mechanism for users to provide additional details when reporting an issue.

## Technology Stack

### Web Platform

- Frontend:
  - HTML, CSS, JavaScript (React)
- Backend:
  - Node.js or Python Flask
- Database:
  - Firebase, Supabase
- AI Integration:
  - Use pre-trained models or train a custom model using libraries like TensorFlow or PyTorch

### Mobile App

- Framework:
  - React Native or Flutter

## Deployment

- Deploy the web platform on a reliable hosting provider like vercel
- Distribute the mobile app through app stores obv :) (Google Play Store, Apple App Store).

yeah thats more than enough :)
