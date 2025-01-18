---
title: Testing Page
description: 
published: true
date: 2025-01-18T18:50:47.007Z
tags: 
editor: markdown
dateCreated: 2025-01-18T18:44:44.199Z
---

# Test


<div class="chat-container">
    <div class="chat-bar">
        <img src="your-avatar-image-url.png" alt="Avatar" class="avatar">
        <span class="command-text typing">/create player</span>
        <div class="parameters hidden">
            <div class="parameter">
                <span class="parameter-label">user</span>
                <span class="parameter-value typing-value">test</span>
            </div>
            <div class="parameter">
                <span class="parameter-label">region</span>
                <span class="parameter-value typing-value">test</span>
            </div>
            <div class="parameter">
                <span class="parameter-label">game-name</span>
                <span class="parameter-value typing-value">test</span>
            </div>
            <div class="parameter">
                <span class="parameter-label">tag</span>
                <span class="parameter-value typing-value">test</span>
            </div>
        </div>
        <button class="send-btn">▶</button>
    </div>
</div>

<script>
    // Wait for the command text to finish typing before showing parameters
    document.addEventListener("DOMContentLoaded", () => {
        const commandText = document.querySelector(".command-text");
        const parameters = document.querySelector(".parameters");

        // Set a delay equal to the typing animation of the command
        setTimeout(() => {
            parameters.classList.remove("hidden");

            // Add typing animation delays for each parameter
            const parameterValues = document.querySelectorAll(".typing-value");
            parameterValues.forEach((value, index) => {
                value.style.animationDelay = `${2 + index}s`; // Adjust delay for each value
            });
        }, 2000); // Matches the command-text animation duration
    });
</script>