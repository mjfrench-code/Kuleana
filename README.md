const map = new mapboxgl.Map({
  container: 'map',
  style: 'mapbox://styles/mapbox/standard',
  config: {
    basemap: {
      lightPreset: "dusk",
      colorMotorways: "#2e89ff",
      showPedestrianRoads: false,
      show3dObjects: false
    }
  },
  center: [-73.99059, 40.74012],
  zoom: 11.50,
  bearing: 0.00,
  pitch: 0.00,
});