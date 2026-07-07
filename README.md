# ARTEMIS Python API documentation

Updated package including SurfaceTemp.

Files:

- `index.html`: Swagger UI page with a dropdown for the aggregate catalog and individual service specs.
- `openapi.yaml`: aggregate catalog with documentation prefixes.
- Individual OpenAPI files for ClimateRag, FutureClimate, RandomGen, SensorCluster, SingleSensor and SurfaceTemp.

For direct Swagger "Try it out" calls, select the individual service spec. The aggregate spec is mainly a catalog, because several services can share the same paths.

Expected ARTEMIS development ports:

- ClimateRag: `http://10.0.4.10:8101`
- FutureClimate: `http://10.0.4.10:8102`
- RandomGen: `http://10.0.4.10:8103`
- SensorCluster: `http://10.0.4.10:8104`
- SingleSensor: `http://10.0.4.10:8105`
- SurfaceTemp: `http://10.0.4.10:8106`
