/* Styles specifici per la mappa e tooltip */
#mapWrapper, .map-wrapper {
  display: flex;
  position: relative;
  width: 100%;
  height: 70vh;
  min-height: 400px;
  overflow: hidden;
}

#map {
  width: 100%;
  height: 100%;
  position: relative;
  z-index: 5;
  background: #f5f5f5;
}

/* Forza z-index dei pannelli Leaflet per evitare overlay fuori contesto */
.leaflet-pane, .leaflet-map-pane, .leaflet-tile-pane {
  z-index: 5 !important;
}

/* Tooltip della mappa */
.region-tooltip {
  position: absolute;
  display: none;
  pointer-events: none;
  z-index: 9999;
  background: rgba(0,0,0,0.8);
  color: #fff;
  padding: 6px 10px;
  border-radius: 4px;
  font-size: 0.9rem;
  transform: translate(-50%, -120%);
  white-space: nowrap;
}

/* Nascondi elementi che potrebbero sovrapporsi in modo errato quando sono "hidden" */
.regions-panel-hidden,
.regions-panel-header.hidden,
#regionsList.hidden {
  display: none !important;
}

/* Debug helpers (rimuovili in produzione) */
.map-debug-outline { outline: 1px dashed rgba(255,0,0,0.25); }
