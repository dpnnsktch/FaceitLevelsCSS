# FaceitLevelsCSS
These CSS styles may be useful to you in some project, but most importantly, if you are making a project with these styles, I ask you to at least briefly indicate the author and the official website faceit.com, as this may violate copyright.
These CSS files were not made "Exactly" due to copyright

# LEVELS CSS:
LEVEL 9:
:root {
    --bg-circle: #1e1e1e;
    --ring-empty: #2d2d2d;
    --lvl-10: #ff1a1a;
    --lvl-8-9: #ff7b00;
    --lvl-4-7: #ffb800;
    --lvl-2-3: #00ff7f;
    --lvl-1: #ffffff;
}

/* Уровень 9 специфичные стили */

/* Обязательная структура иконки FACEIT */
.faceit-icon {
    position: relative;
    width: 40px;
    height: 40px;
    background-color: var(--bg-circle);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
}
.ring {
    position: absolute;
    width: 32px;
    height: 32px;
    border-radius: 50%;
    z-index: 1;
}
.center-hole {
    position: absolute;
    width: 24px;
    height: 24px;
    background-color: var(--bg-circle);
    border-radius: 50%;
    z-index: 2;
    display: flex;
    align-items: center;
    justify-content: center;
}
.num {
    font-size: 14px;
    font-weight: 700;
    transform: skewX(-5deg);
}

.lvl-9 .ring { background: conic-gradient(var(--lvl-8-9) 250deg, var(--ring-empty) 0 310deg, transparent 0); transform: rotate(-235deg); }
.lvl-9 .num { color: var(--lvl-8-9); }
