# Welcome to my Portfolio

I am a Mechanical Engineering student focusing on system dynamics, numerical simulation, and fluid-structure interaction. Below is a showcase of my core engineering projects.

<style>
    .notion-container {
        background-color: #121212;
        color: #e0e0e0;
        padding: 30px;
        border-radius: 8px;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    .notion-row {
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 40px 0;
        border-bottom: 1px solid #2d2d2d;
    }
    .notion-row:last-child {
        border-bottom: none;
    }
    .notion-row.reverse {
        flex-direction: row-reverse;
    }
    .project-text {
        flex: 1;
        padding-right: 30px;
    }
    .notion-row.reverse .project-text {
        padding-right: 0;
        padding-left: 30px;
    }
    .project-image {
        flex: 0 0 35%;
        max-width: 35%;
    }
    .project-image img {
        width: 100%;
        border-radius: 4px;
        display: block;
    }
    .project-title {
        font-size: 1.6rem;
        font-weight: 600;
        margin-bottom: 15px;
        color: #ffffff;
    }
    .project-title a {
        color: #ffffff !important;
        text-decoration: none;
    }
    .project-title a:hover {
        color: #0076ff !important;
    }
    .project-desc {
        font-size: 1rem;
        line-height: 1.6;
        color: #b0b0b0;
    }
    .disclaimer-section {
        margin-top: 50px;
        padding-top: 20px;
        border-top: 1px solid #ddd;
        font-size: 0.85rem;
        color: #666;
    }
</style>

<div class="notion-container">
    <div class="notion-row">
        <div class="project-text">
            <div class="project-title">
                <a href="vortex-induced-vibrations/">Vortex-Induced Vibration | Ansys Fluent | 2026</a>
            </div>
            <div class="project-desc">
                This project studies vortex-induced vibrations of a 2D cylinder using CFD with a SDOF structural model, capturing vortex shedding and the resulting oscillations via a transient dynamic mesh while analyzing the wake-structure interaction in time and frequency domains.
            </div>
        </div>
        <div class="project-image">
            <img src="vortex-induced-vibrations/images/viv_model.png" alt="Vortex-Induced Vibration">
        </div>
    </div>
    <div class="notion-row reverse">
        <div class="project-text">
            <div class="project-title">
                <a href="cfd-fem-coupling/">CFD-FEM One-Way Coupling | Ansys Products | 2025</a>
            </div>
            <div class="project-desc">
                A structural simulation project focused on the analysis and optimization of a lightweight aircraft wing through FEM, aerodynamic load evaluation, modal analysis, and harmonic response assessment using composite materials.
            </div>
        </div>
        <div class="project-image">
            <img src="cfd-fem-coupling/images/wing-preview.png" alt="CFD-FEM Coupling">
        </div>
    </div>
</div>

<div class="disclaimer-section">
    <p><strong>Disclaimer:</strong> The projects, models, and simulations presented in this portfolio are intended solely for academic and illustrative purposes. The numerical data and results are not certified and should not be used for real-world industrial or commercial engineering applications.</p>
</div>
