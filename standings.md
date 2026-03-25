<style>
.btl-layout {
  display: block;
}

.btl-sidebar {
  width: 240px;
  position: fixed;
  left: 0;
  top: 0;
  height: 100vh;
  padding: 20px 16px;
  box-sizing: border-box;
  background: #0f172a;
  color: #e2e8f0;
  overflow-y: auto;
}

.btl-sidebar h2 {
  margin: 0 0 16px;
  font-size: 1rem;
}

.btl-sidebar a {
  display: block;
  color: #cbd5e1;
  text-decoration: none;
  padding: 10px 12px;
  border-radius: 8px;
  margin-bottom: 8px;
}

.btl-sidebar a:hover,
.btl-sidebar a.active {
  background: #1e293b;
  color: #ffffff;
}

.btl-main {
  display: block;
}

@media (min-width: 901px) {
  .markdown-body {
    margin-left: 264px;
    max-width: none;
    padding-right: 24px;
  }
}

.sheet-frame {
  width: 100%;
  height: 80vh;
  border: 1px solid #cbd5e1;
  border-radius: 10px;
  background: #ffffff;
}

@media (max-width: 900px) {
  .btl-layout {
    display: block;
  }

  .btl-sidebar {
    width: 100%;
    height: auto;
    position: static;
    overflow-y: visible;
  }

  .markdown-body {
    margin-left: 0;
  }

  .sheet-frame {
    height: 70vh;
  }
}
</style>

<div class="btl-layout">
  <nav class="btl-sidebar" aria-label="Main navigation">
    <h2>Baltic Trackmania</h2>
    <a href="./index.html">Rulebook</a>
    <a class="active" href="./standings.html">Standings Sheet</a>
  </nav>
</div>

# Baltic Trackmania Standings

This page uses the original Google Sheet directly.

If the embed does not load, open it here:
<a href="https://docs.google.com/spreadsheets/d/150X93FQv6Vqw8MD8mITO9o-PDFghdUhsdWdTUFFVPWY/edit?gid=1311952435#gid=1311952435" target="_blank" rel="noopener noreferrer">Google Sheet</a>

<iframe
  class="sheet-frame"
  src="https://docs.google.com/spreadsheets/d/150X93FQv6Vqw8MD8mITO9o-PDFghdUhsdWdTUFFVPWY/preview?gid=1311952435"
  title="Baltic Trackmania Standings"
  loading="lazy">
</iframe>
