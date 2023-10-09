# Enderase - Legal Knowledge Chatbot

Welcome to the Enderase GitHub organization! This is the central hub for the Enderase project and its repositories. Enderase is a legal knowledge chatbot designed to provide accurate and context-aware answers to legal queries. Below, you'll find an overview of the repositories within this organization.

## Structure

The repository is structured as follows:

1. **LLM-Server Repository:** The `LLM-Server` repository contains the backend code of the Enderase chatbot. This includes API endpoints, Generative AI models, and the Vector database (ChromaDB) for storing legal documents. Python and the Flask framework power this backend.

2. **Backend Repository:** The `backend` repository contains the backend code for Enderase User handling. This includes API endpoints for managing admins, users, conversations, and lawyer infomrations. It also includes an encapsulation of the LLM-Server inaddition to the Mongodb database for storing data related to users. Nodejs and Express using Typescript powers this server.

3. **ReactApp Repository:** In the `ReactApp` repository, you'll find the frontend code for the Enderase chatbot. Implemented using JavaScript and React, this repository also includes HTML, CSS, and JavaScript files for the user interface.

4. **FlutterApp Repository:** The `FlutterApp` repository contains the client app for Enderase, enhancing the mobile user experience. It is implemented using the Flutter framework.

5. **TelegramBot Repository:** In the `TelegramBot` repository, you'll find the Telegram bot for Enderase. It is implemented using Node.js and the Telegraf library, allowing real-time interactions via the Telegram messaging platform.

6. **.github Repository:** The `.github` repository is used to display the README on the organization's homepage, providing an overview of the Enderase project and its repositories.

> *You can see how our system works by visiting [here](https://app.eraser.io/workspace/o9obcdn3wqSffPlZJbwV?origin=share)*

## Purpose

The purpose of this repository is to provide a collaborative space for the development and improvement of the Enderase chatbot. By making the repository publicly accessible, we aim to foster community engagement. Developers, contributors, and users can explore the codebase, report issues, and suggest enhancements, contributing to the growth of Enderase as a valuable legal knowledge resource.

## How Generative AI Models are Solving the Problem

Enderase leverages Generative AI models to enhance its functionality, particularly in providing precise answers to legal queries. These models, including the `Palm's text-bison-001` model, have been fine-tuned to interpret and process user questions, ensuring accuracy and relevance. Additionally, the `Palm's embedding-gecko-001` model is used for creating vector embeddings, aiding in semantic search and contextual responses.

By incorporating Generative AI models into Enderase, we enable users to access accurate legal information, with responses generated based on a deep understanding of legal documents. This advanced technology ensures that users receive meaningful and context-aware answers to their legal questions, simplifying legal research for professionals and individuals alike. Enderase's use of Generative AI models significantly enhances the precision and accessibility of legal knowledge.
