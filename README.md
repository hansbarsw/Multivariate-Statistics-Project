# Multivariate-Statistics-Project
## Dataset Description

This dataset contains observations of celestial objects, including galaxies, stars, and quasars. Below is a description of each column:

- **alpha**: Celestial longitude of the object.
- **delta**: Celestial latitude of the object.
- **u**: Ultraviolet magnitude of the object.
- **g**: Green magnitude of the object.
- **r**: Red magnitude of the object.
- **i**: Near-Infrared magnitude of the object.
- **z**: Further-Infrared magnitude of the object.
- **run_ID**: ID of the observation run that captured the object.
- **rereun_ID**: Rerun number specifying how the image was processed.
- **cam_col**: Camera column identifying the scanline within the run.
- **field_ID**: Field number used to identify each field.
- **spec_obj_ID**: Unique ID for optical spectroscopic objects (two observations with the same `spec_obj_ID` must share the same class).
- **class**: Object classification - Galaxy, Star, or Quasar.
- **redshift**: A measure of how much the object's light is shifted due to the expansion of the universe.
- **plate**: Spectroscopic plate number used to capture the object's spectrum.
- **MJD**: Modified Julian Date indicating when the SDSS data was taken.
- **fiber_ID**: Fiber ID identifying the fiber that pointed the light at the focal plane in each observation.
