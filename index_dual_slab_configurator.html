<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Slab Riser Configurator</title>

  <style>
    :root {
      --bg: #0f172a;
      --card: #111827;
      --text: #f8fafc;
      --muted: #94a3b8;
      --accent: #facc15;
      --accent2: #38bdf8;
      --border: rgba(255,255,255,0.12);
    }

    * { box-sizing: border-box; }

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
      .grid { grid-template-columns: 1fr; }
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

    input:focus, select:focus {
      border-color: var(--accent2);
    }

    .field { margin-bottom: 14px; }

    .small {
      font-size: 0.82rem;
      color: var(--muted);
      line-height: 1.45;
      margin-top: 6px;
    }

    .result-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 12px;
      margin-bottom: 18px;
    }

    @media (max-width: 700px) {
      .result-grid { grid-template-columns: 1fr; }
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

    .case-label {
      position: absolute;
      color: rgba(255,255,255,0.88);
      font-size: 0.78rem;
      font-weight: 700;
      background: rgba(15,23,42,0.82);
      border: 1px solid rgba(255,255,255,0.18);
      border-radius: 999px;
      padding: 5px 9px;
      z-index: 12;
      pointer-events: none;
    }

    .case-frame {
      position: absolute;
      border: 5px solid rgba(255,255,255,0.9);
      border-radius: 0;
      background: rgba(255,255,255,0.025);
      z-index: 10;
      pointer-events: none;
    }

    .module {
      position: absolute;
      background: rgba(56,189,248,0.33);
      border: 1px solid rgba(125,211,252,0.78);
      border-radius: 8px;
      display: grid;
      overflow: hidden;
      z-index: 3;
    }

    .module > div:not(.module-info) {
      border-bottom: 1px solid rgba(255,255,255,0.45);
    }

    .module-info {
      position: absolute;
      inset: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      font-size: 0.62rem;
      font-weight: 700;
      color: rgba(255,255,255,0.92);
      line-height: 1.2;
      pointer-events: none;
      padding: 4px;
    }

    .spacer {
      position: absolute;
      background: rgba(250,204,21,0.34);
      border: 1px solid rgba(253,224,71,0.95);
      border-radius: 5px;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 0.7rem;
      font-weight: 700;
      z-index: 3;
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
      .outputs { grid-template-columns: 1fr; }
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
    <h1>Slab Riser Configurator</h1>
    <p class="subtitle">
      Choose your slab type, enter the inside case measurements, and the configurator automatically finds the best riser and spacer setup.
    </p>
  </header>

  <div class="grid">

    <section class="card">
      <h2>Case measurements</h2>

      <div class="field">
        <label for="slabType">Slab type</label>
        <select id="slabType">
          <option value="toploader">Toploader / Hardcase</option>
          <option value="graded">Graded Slab</option>
        </select>
      </div>

      <div class="field">
        <label for="caseLength">Inside case length, mm</label>
        <input id="caseLength" type="number" value="850" min="1" step="0.1">
      </div>

      <div class="field">
        <label for="caseWidth">Inside case width/depth, mm</label>
        <input id="caseWidth" type="number" value="600" min="1" step="0.1">
        <div class="small">All other settings are optimized automatically.</div>
      </div>

      <div id="advancedSettings" style="display:none;">
        <input id="lengthClearance" type="number" value="2">
        <input id="spacerShrink" type="number" value="1.5">
        <input id="riserMaxLength" type="number" value="250">
        <input id="spacerMaxLength" type="number" value="300">
        <input id="gap" type="number" value="1.2">
      </div>
    </section>

    <section class="card">

      <h2>Recommended values</h2>

      <div class="result-grid">

        <div class="stat">
          <div class="label">Model Length</div>
          <div class="value" id="modelLength">—</div>
        </div>

        <div class="stat">
          <div class="label">SUMMARY</div>
          <div class="value" id="shortSummary" style="font-size:1rem; line-height:1.35;">—</div>
        </div>

        <div class="stat">
          <div class="label">Empty Space</div>
          <div class="value" id="emptySpace">—</div>
        </div>

      </div>

      <div id="warning" class="note warn" style="display:none;"></div>

      <div class="preview">
        <h2 style="margin-bottom:12px;">Layout preview</h2>
        <div class="case-box" id="caseBox"></div>
        <div class="small" style="margin-top:10px;">
          White frame = inside case size. Blue = riser modules. Yellow = spacer area.
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
    "slabType",
    "caseLength",
    "caseWidth",
    "lengthClearance",
    "spacerShrink",
    "riserMaxLength",
    "spacerMaxLength",
    "gap"
  ];

  ids.forEach(id =>
    document.getElementById(id).addEventListener("input", calculate)
  );

  function cleanNumber(value, decimals = 1) {
    const factor = Math.pow(10, decimals);
    const rounded = Math.floor(value * factor) / factor;
    return Number.isInteger(rounded)
      ? String(rounded)
      : rounded.toFixed(decimals);
  }

  function calculate() {

    const slabType = document.getElementById("slabType").value;

    const caseLength = Number(document.getElementById("caseLength").value);
    const caseWidth = Number(document.getElementById("caseWidth").value);

    const lengthClearance = Number(document.getElementById("lengthClearance").value);
    const spacerShrink = Number(document.getElementById("spacerShrink").value);
    const riserMaxLength = Number(document.getElementById("riserMaxLength").value);
    const spacerMaxLength = Number(document.getElementById("spacerMaxLength").value);
    const gap = Number(document.getElementById("gap").value);

    // ======================================================
    // SLAB TYPE
    // ======================================================

    const panelLength =
      slabType === "graded"
        ? 93.7
        : 58.7;

    const safeWidthClearance = 1.5;
    const usableCaseWidth = Math.max(0, caseWidth - safeWidthClearance);

    // ======================================================
    // PANEL OPTIONS
    // ======================================================

    const rowOptions = [
      {
        panelCount: 3,
        moduleDepth: panelLength * 3 + gap
      },
      {
        panelCount: 2,
        moduleDepth: panelLength * 2 + gap
      },
      {
        panelCount: 1,
        moduleDepth: panelLength + gap
      }
    ];

    const allCandidates = [];

    function testCombos(combo, startIndex) {

      const usedWidth =
        combo.reduce((sum, row) => sum + row.moduleDepth, 0);

      const emptySpace =
        caseWidth - usedWidth;

      if (
        usedWidth <= usableCaseWidth &&
        combo.length > 0
      ) {

        const counts = {
          1: 0,
          2: 0,
          3: 0
        };

        combo.forEach(row =>
          counts[row.panelCount]++
        );

        const totalPanels =
          combo.reduce(
            (sum, row) => sum + row.panelCount,
            0
          );

        allCandidates.push({
          rows: combo.length,
          rowList: [...combo],
          usedWidth,
          emptySpace,
          totalPanels,
          counts
        });
      }

      for (
        let i = startIndex;
        i < rowOptions.length;
        i++
      ) {

        const option = rowOptions[i];

        if (
          usedWidth + option.moduleDepth
          <= usableCaseWidth
        ) {
          testCombos(
            [...combo, option],
            i
          );
        }
      }
    }

    testCombos([], 0);

    // ======================================================
    // CHOOSE BEST CONFIGURATION
    // ======================================================

    let best = null;

    if (allCandidates.length > 0) {

      best = allCandidates.sort((a, b) => {

        // Max capacity first
        if (b.totalPanels !== a.totalPanels)
          return b.totalPanels - a.totalPanels;

        // Prefer 3-panel modules
        if (b.counts[3] !== a.counts[3])
          return b.counts[3] - a.counts[3];

        // Then 2-panel modules
        if (b.counts[2] !== a.counts[2])
          return b.counts[2] - a.counts[2];

        // Least unused space
        if (a.emptySpace !== b.emptySpace)
          return a.emptySpace - b.emptySpace;

        return a.rows - b.rows;

      })[0];
    }

    const rows = best ? best.rows : 0;
    const emptySpace = best ? best.emptySpace : caseWidth;
    const rowList = best ? best.rowList : [];

    // ======================================================
    // MODULE LENGTH
    // ======================================================

    const columns =
      Math.ceil(
        caseLength /
        riserMaxLength
      );

    const modelLengthRaw =
      (caseLength - lengthClearance) /
      columns;

    const modelLength =
      Math.floor(modelLengthRaw);

    // ======================================================
    // SPACER
    // ======================================================

    const spacerPartCount =
      Math.ceil(
        caseLength /
        spacerMaxLength
      );

    const spacerPartLength =
      Math.floor(
        (caseLength - lengthClearance) /
        spacerPartCount
      );

    // ======================================================
    // WARNINGS
    // ======================================================

    const warning =
      document.getElementById("warning");

    warning.style.display = "none";
    warning.textContent = "";

    if (!best) {
      warning.style.display = "block";
      warning.textContent =
        "Case width is too small for a riser module.";
    }

    // ======================================================
    // OUTPUT
    // ======================================================

    document.getElementById("modelLength").textContent =
      cleanNumber(modelLength, 0);

    document.getElementById("emptySpace").textContent =
      cleanNumber(emptySpace, 1);

    const counts = {
      1: 0,
      2: 0,
      3: 0
    };

    rowList.forEach(row =>
      counts[row.panelCount]++
    );

    const comboParts = [];

    for (
      let panels = 3;
      panels >= 1;
      panels--
    ) {

      if (counts[panels] > 0) {

        const rowQty = counts[panels];
        const moduleQty = columns * rowQty;

        comboParts.push(
          `${moduleQty}× ${panels}-panel modules`
        );
      }
    }

    document.getElementById("shortSummary").innerHTML =
      comboParts.join("<br>");

    // ======================================================
    // RISER INPUT
    // ======================================================

    let riserText =
`TYPE = ${slabType === "graded" ? "GRADED SLAB" : "TOPLOADER"}
MODEL_LENGTH = ${cleanNumber(modelLength, 0)}
PANEL_LENGTH = ${cleanNumber(panelLength, 1)}
`;

    for (
      let panels = 3;
      panels >= 1;
      panels--
    ) {

      if (counts[panels] > 0) {

        const rowQty = counts[panels];
        const moduleQty = columns * rowQty;

        const rowDepth =
          panelLength * panels + gap;

        riserText +=
`
${moduleQty} × modules:
PANEL_COUNT = ${panels}
MODULE_SIZE = ${cleanNumber(modelLength, 0)} × ${cleanNumber(rowDepth, 1)} mm
`;
      }
    }

    document.getElementById("riserOutput").textContent =
      riserText.trim();

    // ======================================================
    // SPACER INPUT
    // ======================================================

    document.getElementById("spacerOutput").textContent =
`CASE_LENGTH     = ${cleanNumber(caseLength, 0)}
EMPTY_SPACE     = ${cleanNumber(emptySpace, 1)}
SPACER_SHRINK   = ${cleanNumber(spacerShrink, 1)}
MAX_PART_LENGTH = ${cleanNumber(spacerMaxLength, 0)}

SPACER_PARTS    = ${spacerPartCount}
PART_LENGTH     ≈ ${cleanNumber(spacerPartLength, 0)}`;

    // ======================================================
    // PREVIEW
    // ======================================================

    drawPreview({
      caseLength,
      caseWidth,
      columns,
      rows,
      modelLength,
      emptySpace,
      rowList
    });
  }

  // ======================================================
  // PREVIEW
  // ======================================================

  function drawPreview(data) {

    const box =
      document.getElementById("caseBox");

    box.innerHTML = "";

    const pad = 34;

    const boxW =
      box.clientWidth - pad * 2;

    const boxH =
      box.clientHeight - pad * 2;

    const scale =
      Math.min(
        boxW / data.caseLength,
        boxH / data.caseWidth
      );

    const layoutW =
      data.caseLength * scale;

    const layoutH =
      data.caseWidth * scale;

    const startX =
      (box.clientWidth - layoutW) / 2;

    const startY =
      (box.clientHeight - layoutH) / 2;

    // CASE FRAME
    const frame =
      document.createElement("div");

    frame.className = "case-frame";
    frame.style.left = startX + "px";
    frame.style.top = startY + "px";
    frame.style.width = layoutW + "px";
    frame.style.height = layoutH + "px";

    box.appendChild(frame);

    // LENGTH LABEL
    const lengthLabel =
      document.createElement("div");

    lengthLabel.className = "case-label";
    lengthLabel.textContent =
      `${cleanNumber(data.caseLength, 0)} mm length`;

    lengthLabel.style.left =
      (startX + layoutW / 2) + "px";

    lengthLabel.style.top =
      Math.max(4, startY - 26) + "px";

    lengthLabel.style.transform =
      "translateX(-50%)";

    box.appendChild(lengthLabel);

    // WIDTH LABEL
    const widthLabel =
      document.createElement("div");

    widthLabel.className = "case-label";
    widthLabel.textContent =
      `${cleanNumber(data.caseWidth, 0)} mm width`;

    widthLabel.style.left =
      Math.max(4, startX - 28) + "px";

    widthLabel.style.top =
      (startY + layoutH / 2) + "px";

    widthLabel.style.transform =
      "translate(-50%, -50%) rotate(-90deg)";

    box.appendChild(widthLabel);

    // MODULES
    let currentY = startY;

    for (
      let r = 0;
      r < data.rowList.length;
      r++
    ) {

      const row = data.rowList[r];

      for (
        let c = 0;
        c < data.columns;
        c++
      ) {

        const mod =
          document.createElement("div");

        mod.className = "module";

        mod.style.left =
          (
            startX +
            c *
            data.modelLength *
            scale
          ) +
          "px";

        mod.style.top =
          currentY +
          "px";

        mod.style.width =
          Math.max(
            2,
            data.modelLength *
            scale -
            2
          ) +
          "px";

        mod.style.height =
          Math.max(
            2,
            row.moduleDepth *
            scale -
            2
          ) +
          "px";

        mod.style.gridTemplateRows =
          `repeat(${row.panelCount}, 1fr)`;

        for (
          let i = 0;
          i < row.panelCount;
          i++
        ) {
          const panel =
            document.createElement("div");

          mod.appendChild(panel);
        }

        const info =
          document.createElement("div");

        info.className =
          "module-info";

        info.innerHTML =
`${cleanNumber(data.modelLength, 0)} × ${cleanNumber(row.moduleDepth, 1)} mm<br>
${row.panelCount} panel${row.panelCount > 1 ? "s" : ""}`;

        mod.appendChild(info);
        box.appendChild(mod);
      }

      currentY +=
        row.moduleDepth *
        scale;
    }

    // SPACER
    if (data.emptySpace > 0) {

      const spacer =
        document.createElement("div");

      spacer.className =
        "spacer";

      spacer.style.left =
        (startX + 3) +
        "px";

      spacer.style.top =
        currentY +
        "px";

      spacer.style.width =
        Math.max(
          2,
          layoutW - 6
        ) +
        "px";

      spacer.style.height =
        Math.max(
          12,
          data.emptySpace *
          scale -
          3
        ) +
        "px";

      spacer.textContent =
        `SPACER ${cleanNumber(data.emptySpace, 1)} mm`;

      box.appendChild(spacer);
    }
  }

  async function copyText(elementId) {

    const text =
      document
        .getElementById(elementId)
        .textContent;

    await navigator.clipboard.writeText(text);
  }

  calculate();

  window.addEventListener(
    "resize",
    calculate
  );

</script>

</body>
</html>
