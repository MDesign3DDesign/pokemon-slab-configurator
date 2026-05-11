<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pokémon Slab Riser Configurator</title>
  <style>
    :root {
      --bg: #0f172a;
      --card: #111827;
      --card2: #1f2937;
      --text: #f8fafc;
      --muted: #94a3b8;
      --accent: #facc15;
      --accent2: #38bdf8;
      --border: rgba(255,255,255,0.12);
      --danger: #fb7185;
      --ok: #4ade80;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background:
        radial-gradient(circle at top left, rgba(250,204,21,0.16), transparent 28%),
        radial-gradient(circle at top right, rgba(56,189,248,0.14), transparent 28%),
        var(--bg);
      color: var(--text);
      min-height: 100vh;
      padding: 24px;
    }

    .wrap {
      max-width: 1120px;
      margin: 0 auto;
    }

    header {
      text-align: center;
      margin-bottom: 28px;
    }

    h1 {
      font-size: clamp(2rem, 5vw, 4rem);
      margin: 0 0 10px;
      letter-spacing: -0.04em;
    }

    .subtitle {
      color: var(--muted);
      font-size: 1.05rem;
      max-width: 720px;
      margin: 0 auto;
      line-height: 1.5;
    }

    .grid {
      display: grid;
      grid-template-columns: 360px 1fr;
      gap: 20px;
    }

    @media (max-width: 850px) {
      .grid {
        grid-template-columns: 1fr;
      }
    }

    .card {
      background: linear-gradient(180deg, rgba(255,255,255,0.08), rgba(255,255,255,0.04));
      border: 1px solid var(--border);
      border-radius: 24px;
      padding: 20px;
      box-shadow: 0 20px 60px rgba(0,0,0,0.25);
    }

    .card h2 {
      margin: 0 0 16px;
      font-size: 1.25rem;
    }

    label {
      display: block;
      font-size: 0.9rem;
      color: var(--muted);
      margin-bottom: 7px;
    }

    input, select {
      width: 100%;
      padding: 12px 13px;
      border-radius: 14px;
      border: 1px solid var(--border);
      background: rgba(15,23,42,0.9);
      color: var(--text);
      font-size: 1rem;
      outline: none;
    }

    input:focus {
      border-color: var(--accent2);
    }

    .field {
      margin-bottom: 14px;
    }

    .small {
      font-size: 0.82rem;
      color: var(--muted);
      line-height: 1.45;
      margin-top: 6px;
    }

    .result-grid {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 12px;
      margin-bottom: 18px;
    }

    @media (max-width: 700px) {
      .result-grid {
        grid-template-columns: repeat(2, 1fr);
      }
    }

    .stat {
      background: rgba(15,23,42,0.72);
      border: 1px solid var(--border);
      border-radius: 18px;
      padding: 14px;
    }

    .stat .label {
      color: var(--muted);
      font-size: 0.78rem;
      margin-bottom: 6px;
    }

    .stat .value {
      font-weight: 800;
      font-size: 1.45rem;
    }

    .preview {
      background: rgba(15,23,42,0.76);
      border: 1px solid var(--border);
      border-radius: 22px;
      padding: 16px;
      margin-top: 12px;
    }

    .case-box {
      position: relative;
      height: 360px;
      border: 2px dashed rgba(255,255,255,0.28);
      border-radius: 18px;
      background: rgba(255,255,255,0.035);
      overflow: hidden;
    }

    .module {
      position: absolute;
      background: rgba(56,189,248,0.33);
      border: 1px solid rgba(125,211,252,0.78);
      border-radius: 8px;
      display: grid;
      grid-template-rows: repeat(3, 1fr);
      overflow: hidden;
    }

    .module div {
      border-bottom: 1px solid rgba(255,255,255,0.45);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 0.65rem;
      color: white;
    }

    .module div:last-child {
      border-bottom: 0;
    }

    .spacer {
      position: absolute;
      background: rgba(250,204,21,0.34);
      border: 1px solid rgba(253,224,71,0.95);
      border-radius: 8px;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 0.7rem;
      font-weight: 700;
      writing-mode: vertical-rl;
      text-orientation: mixed;
    }

    pre {
      white-space: pre-wrap;
      word-break: break-word;
      margin: 0;
      padding: 16px;
      border-radius: 18px;
      background: rgba(2,6,23,0.72);
      border: 1px solid var(--border);
      color: #e2e8f0;
      line-height: 1.55;
      font-size: 0.95rem;
    }

    .outputs {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 14px;
      margin-top: 16px;
    }

    @media (max-width: 800px) {
      .outputs {
        grid-template-columns: 1fr;
      }
    }

    button {
      cursor: pointer;
      border: 0;
      padding: 12px 15px;
      border-radius: 14px;
      background: var(--accent);
      color: #111827;
      font-weight: 800;
      margin-top: 10px;
      width: 100%;
    }

    button:hover {
      filter: brightness(1.04);
    }

    .note {
      margin-top: 14px;
      padding: 13px 14px;
      border-radius: 16px;
      background: rgba(74,222,128,0.10);
      border: 1px solid rgba(74,222,128,0.25);
      color: #bbf7d0;
      font-size: 0.9rem;
      line-height: 1.5;
    }

    .warn {
      background: rgba(251,113,133,0.12);
      border-color: rgba(251,113,133,0.35);
      color: #fecdd3;
    }

    footer {
      color: var(--muted);
      text-align: center;
      margin-top: 28px;
      font-size: 0.86rem;
    }
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <h1>Pokémon Slab Riser Configurator</h1>
      <p class="subtitle">
        Enter the inside measurements of your display case and copy the values into MakerWorld Parametric Model Maker.
      </p>
    </header>

    <div class="grid">
      <section class="card">
        <h2>Case measurements</h2>

        <div class="field">
          <label for="caseLength">Inside case length, mm</label>
          <input id="caseLength" type="number" value="850" min="1" step="0.1">
        </div>

        <div class="field">
          <label for="caseWidth">Inside case width/depth, mm</label>
          <input id="caseWidth" type="number" value="600" min="1" step="0.1">
        </div>

        <div class="field">
          <label for="lengthClearance">Total length clearance, mm</label>
          <input id="lengthClearance" type="number" value="2" min="0" step="0.1">
          <div class="small">Same logic as the example: about 1 mm clearance on each end.</div>
        </div>

        <div class="field">
          <label for="spacerShrink">Spacer shrink, mm</label>
          <input id="spacerShrink" type="number" value="1.5" min="0" step="0.1">
          <div class="small">Spacer is made this much smaller than the remaining empty space.</div>
        </div>

        <div class="field">
          <label for="riserMaxLength">Max riser module length, mm</label>
          <input id="riserMaxLength" type="number" value="250" min="1" step="1">
        </div>

        <div class="field">
          <label for="spacerMaxLength">Max spacer part length, mm</label>
          <input id="spacerMaxLength" type="number" value="300" min="1" step="1">
        </div>

        <div class="field">
          <label for="panelLength">Panel length, mm</label>
          <input id="panelLength" type="number" value="58.7" min="1" step="0.1">
        </div>

        <div class="field">
          <label for="gap">Gap, mm</label>
          <input id="gap" type="number" value="1.2" min="0" step="0.1">
        </div>

        <div class="note">
          The configurator uses max 3 panels per riser and calculates the remaining space as spacer area.
        </div>
      </section>

      <section class="card">
        <h2>Recommended values</h2>

        <div class="result-grid">
          <div class="stat">
            <div class="label">MODEL_LENGTH</div>
            <div class="value" id="modelLength">—</div>
          </div>
          <div class="stat">
            <div class="label">PANEL_COUNT</div>
            <div class="value" id="panelCount">—</div>
          </div>
          <div class="stat">
            <div class="label">Riser grid</div>
            <div class="value" id="riserGrid">—</div>
          </div>
          <div class="stat">
            <div class="label">EMPTY_SPACE</div>
            <div class="value" id="emptySpace">—</div>
          </div>
        </div>

        <div id="warning" class="note warn" style="display:none;"></div>

        <div class="preview">
          <h2 style="margin-bottom:12px;">Layout preview</h2>
          <div class="case-box" id="caseBox"></div>
          <div class="small" style="margin-top:10px;">
            Blue = riser modules. Yellow = spacer area.
          </div>
        </div>

        <div class="outputs">
          <div>
            <h2>Riser input</h2>
            <pre id="riserOutput"></pre>
            <button onclick="copyText('riserOutput')">Copy riser values</button>
          </div>

          <div>
            <h2>Spacer input</h2>
            <pre id="spacerOutput"></pre>
            <button onclick="copyText('spacerOutput')">Copy spacer values</button>
          </div>
        </div>
      </section>
    </div>

    <footer>
      Free configurator for slab riser and spacer values.
    </footer>
  </div>

  <script>
    const ids = [
      "caseLength",
      "caseWidth",
      "lengthClearance",
      "spacerShrink",
      "riserMaxLength",
      "spacerMaxLength",
      "panelLength",
      "gap"
    ];

    ids.forEach(id => document.getElementById(id).addEventListener("input", calculate));

    function cleanNumber(value, decimals = 1) {
      const rounded = Math.floor(value * Math.pow(10, decimals)) / Math.pow(10, decimals);
      return Number.isInteger(rounded) ? String(rounded) : rounded.toFixed(decimals);
    }

    function calculate() {
      const caseLength = Number(document.getElementById("caseLength").value);
      const caseWidth = Number(document.getElementById("caseWidth").value);
      const lengthClearance = Number(document.getElementById("lengthClearance").value);
      const spacerShrink = Number(document.getElementById("spacerShrink").value);
      const riserMaxLength = Number(document.getElementById("riserMaxLength").value);
      const spacerMaxLength = Number(document.getElementById("spacerMaxLength").value);
      const panelLength = Number(document.getElementById("panelLength").value);
      const gap = Number(document.getElementById("gap").value);

      const panelCount = 3;
      const moduleDepth = panelLength * panelCount + gap;

      const columns = Math.ceil(caseLength / riserMaxLength);
      const modelLengthRaw = (caseLength - lengthClearance) / columns;
      const modelLength = Math.floor(modelLengthRaw);

      const rows = Math.floor(caseWidth / moduleDepth);
      const usedWidth = rows * moduleDepth;
      const emptySpace = caseWidth - usedWidth;

      const spacerPartCount = Math.ceil(caseLength / spacerMaxLength);
      const spacerPartLength = Math.floor((caseLength - lengthClearance) / spacerPartCount);

      const warning = document.getElementById("warning");
      warning.style.display = "none";
      warning.textContent = "";

      if (rows < 1) {
        warning.style.display = "block";
        warning.textContent = "Case width is too small for one 3-panel riser module. Try a smaller panel count or larger case width.";
      } else if (emptySpace <= 0) {
        warning.style.display = "block";
        warning.textContent = "No spacer area is left with these measurements.";
      }

      document.getElementById("modelLength").textContent = cleanNumber(modelLength, 0);
      document.getElementById("panelCount").textContent = panelCount;
      document.getElementById("riserGrid").textContent = columns + " × " + rows;
      document.getElementById("emptySpace").textContent = cleanNumber(emptySpace, 1);

      document.getElementById("riserOutput").textContent =
`MODEL_LENGTH = ${cleanNumber(modelLength, 0)}
PANEL_COUNT  = ${panelCount}`;

      document.getElementById("spacerOutput").textContent =
`CASE_LENGTH   = ${cleanNumber(caseLength, 0)}
EMPTY_SPACE   = ${cleanNumber(emptySpace, 1)}
SPACER_SHRINK = ${cleanNumber(spacerShrink, 1)}
MAX_PART_LENGTH = ${cleanNumber(spacerMaxLength, 0)}

// Info:
SPACER_PARTS  = ${spacerPartCount}
PART_LENGTH   ≈ ${cleanNumber(spacerPartLength, 0)}`;

      drawPreview({
        caseLength,
        caseWidth,
        columns,
        rows,
        modelLength,
        moduleDepth,
        emptySpace
      });
    }

    function drawPreview(data) {
      const box = document.getElementById("caseBox");
      box.innerHTML = "";

      const pad = 12;
      const boxW = box.clientWidth - pad * 2;
      const boxH = box.clientHeight - pad * 2;

      const scale = Math.min(boxW / data.caseLength, boxH / data.caseWidth);
      const layoutW = data.caseLength * scale;
      const layoutH = data.caseWidth * scale;
      const startX = (box.clientWidth - layoutW) / 2;
      const startY = (box.clientHeight - layoutH) / 2;

      for (let r = 0; r < data.rows; r++) {
        for (let c = 0; c < data.columns; c++) {
          const mod = document.createElement("div");
          mod.className = "module";
          mod.style.left = (startX + c * data.modelLength * scale) + "px";
          mod.style.top = (startY + r * data.moduleDepth * scale) + "px";
          mod.style.width = (data.modelLength * scale - 2) + "px";
          mod.style.height = (data.moduleDepth * scale - 2) + "px";
          mod.innerHTML = "<div></div><div></div><div></div>";
          box.appendChild(mod);
        }
      }

      if (data.emptySpace > 0) {
        const spacer = document.createElement("div");
        spacer.className = "spacer";
        spacer.style.left = startX + "px";
        spacer.style.top = (startY + data.rows * data.moduleDepth * scale) + "px";
        spacer.style.width = (data.caseLength * scale) + "px";
        spacer.style.height = Math.max(12, data.emptySpace * scale) + "px";
        spacer.style.writingMode = "horizontal-tb";
        spacer.textContent = "SPACER";
        box.appendChild(spacer);
      }
    }

    async function copyText(elementId) {
      const text = document.getElementById(elementId).textContent;
      await navigator.clipboard.writeText(text);
    }

    calculate();
    window.addEventListener("resize", calculate);
  </script>
</body>
</html>
