<style>
.btl-layout {
  display: flex;
  min-height: 100vh;
}

.btl-sidebar {
  width: 240px;
  position: sticky;
  top: 0;
  align-self: flex-start;
  height: 100vh;
  padding: 20px 16px;
  box-sizing: border-box;
  background: #0f172a;
  color: #e2e8f0;
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
  flex: 1;
  min-width: 0;
  padding: 20px 24px;
  box-sizing: border-box;
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
    flex-direction: column;
  }

  .btl-sidebar {
    width: 100%;
    height: auto;
    position: static;
  }

  .btl-main {
    padding: 16px;
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

  <main class="btl-main">
    <h1>Baltic Trackmania Standings</h1>
    <p>This page uses the original Google Sheet directly.</p>
    <p>
      If the embed does not load, open it here:
      <a href="https://docs.google.com/spreadsheets/d/150X93FQv6Vqw8MD8mITO9o-PDFghdUhsdWdTUFFVPWY/edit?gid=1311952435#gid=1311952435" target="_blank" rel="noopener noreferrer">Google Sheet</a>
    </p>

    <iframe
      class="sheet-frame"
      src="https://docs.google.com/spreadsheets/d/150X93FQv6Vqw8MD8mITO9o-PDFghdUhsdWdTUFFVPWY/preview?gid=1311952435"
      title="Baltic Trackmania Standings"
      loading="lazy">
    </iframe>
  </main>
</div>
