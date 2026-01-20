<!-- About Section - Game Dialog Style -->
<section class="about-section" id="about">
    <div class="game-container">
        <!-- Background Image -->
        <div class="game-background">
            <img src="assets/udinus.png" alt="Background" class="bg-image">
            <div class="bg-overlay"></div>
        </div>

        <!-- Character Sprite -->
        <div class="character-container">
            <img src="assets/pixel-removebg-preview.png" alt="Kevin Character" class="character-sprite"
                id="characterSprite">
        </div>

        <!-- Dialog Box -->
        <div class="dialog-box">
            <div class="dialog-header">
                <span class="character-name" id="characterName">Kevin</span>
            </div>
            <div class="dialog-content">
                <p class="dialog-text" id="dialogText"></p>
                <div class="continue-indicator">
                    <span class="arrow-down">▼</span>
                </div>
            </div>
        </div>

        <!-- Dialog Navigation -->
        <div class="dialog-nav">
            <button class="dialog-btn prev-btn" id="prevBtn">◄ Prev</button>
            <span class="dialog-counter" id="dialogCounter">1 / 3</span>
            <button class="dialog-btn next-btn" id="nextBtn">Next ►</button>
        </div>
    </div>
</section>
