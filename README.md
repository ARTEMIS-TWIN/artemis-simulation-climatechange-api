# ARTEMIS Python API Documentation

This package contains:

- `index.html`: Swagger UI with the complete catalog and per-service OpenAPI definitions.
- `openapi.yaml`: complete aggregated catalog. Useful for browsing all endpoints together; not intended for Execute because paths are prefixed to avoid endpoint-name collisions.
- `*-openapi.yaml`: executable per-service OpenAPI definitions using the development VM ports 8101-8106.

Development service URLs:

- ClimateRag: `http://10.0.4.10:8101`
- FutureClimate: `http://10.0.4.10:8102`
- RandomGen: `http://10.0.4.10:8103`
- SensorCluster: `http://10.0.4.10:8104`
- SingleSensor: `http://10.0.4.10:8105`
- SurfaceTemp: `http://10.0.4.10:8106`

When hosted on GitHub Pages, the complete catalog is suitable for public documentation. Browser-based Execute against the internal HTTP VM may still be blocked by mixed-content/CORS/private-network browser policies.
