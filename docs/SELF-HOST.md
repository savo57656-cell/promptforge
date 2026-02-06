# Self-Hosting Guide

This guide will help you set up your own instance of the PromptForge project.

## Prerequisites
- Node.js (version 14.x or higher)
- npm (Node Package Manager)
- MongoDB (version 4.x)

## Steps to Self-Host
1. **Clone the repository**:
   ```bash
   git clone https://github.com/savo57656-cell/promptforge.git
   cd promptforge
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**:
   Create a `.env` file in the root directory and add your configuration.
   ```
   MONGODB_URI=mongodb://localhost:27017/promptforge
   PORT=3000
   ```

4. **Run the application**:
   ```bash
   npm start
   ```

5. **Access the application**:
   Open your browser and go to `http://localhost:3000`

## Troubleshooting
- Ensure MongoDB is running.
- Check console for any error messages.

For more information, visit the [documentation](https://github.com/savo57656-cell/promptforge/wiki).