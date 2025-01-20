<div align="center">
  <a href="https://youtu.be/wtPJxlNjCBE">
    <img src="https://img.youtube.com/vi/wtPJxlNjCBE/0.jpg" alt="Watch the Demo" style="max-width: 80%; border-radius: 8px;" />
  </a>
  <br />
  <strong>Click the thumbnail to watch a demo of the Hotrod effects in action!</strong>
</div>

---

<div align="center">
  <h2><strong>Item Configuration</strong></h2>
  <p>
    Add the following entry to your <code>ox_inventory/data/items.lua</code> file:
  </p>

  <pre>
  <code>
['hotrodtune'] = {
    label = 'Hotrod Tune',
    weight = 1,
    degrade = 100,
    client = {
        image = 'hotrodtune.png',
        export = 'enzo-hotrodshake.applyHotrodTune',
    },
    server = {
        export = 'enzo-hotrodshake.saveHotrodTune',
    },
    consume = 1
}
  </code>
  </pre>
</div>
