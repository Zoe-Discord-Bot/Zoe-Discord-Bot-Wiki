---
title: Testing Page
description: 
published: true
date: 2025-01-18T18:56:53.095Z
tags: 
editor: markdown
dateCreated: 2025-01-18T18:44:44.199Z
---

# Test

<div class="chat-container">
    <div class="chat-bar">
        <img src="your-avatar-image-url.png" alt="Avatar" class="avatar">
        <span class="command-text">/create player</span>
        <div class="parameters">
            <div class="parameter">
                <span class="parameter-label">user</span>
                <span class="parameter-value">test</span>
            </div>
            <div class="parameter">
                <span class="parameter-label">region</span>
                <span class="parameter-value">test</span>
            </div>
            <div class="parameter">
                <span class="parameter-label">game-name</span>
                <span class="parameter-value">test</span>
            </div>
            <div class="parameter">
                <span class="parameter-label">tag</span>
                <span class="parameter-value">test</span>
            </div>
        </div>
        <button class="send-btn">▶</button>
    </div>
</div>

<script>
    document.addEventListener("DOMContentLoaded", () => {
        const commandText = document.querySelector(".command-text");
        const parameters = document.querySelector(".parameters");
        const parameterValues = document.querySelectorAll(".typing-value");

        // Show parameters after the command finishes typing
        setTimeout(() => {
            parameters.classList.remove("hidden");

            // Animate each parameter value sequentially
            parameterValues.forEach((value, index) => {
                setTimeout(() => {
                    value.style.visibility = "visible";
                }, 2000 + index * 2000); // Delay for each parameter
            });
        }, 2000); // Delay matches the typing animation of the command
    });
</script>