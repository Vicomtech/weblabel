<img src="https://raw.githubusercontent.com/Vicomtech/weblabel/main/docs/logo/main_logo_white.svg" width="300" style="display: block;  margin-left: auto;   margin-right: auto" />

WebLabel is a web ecosystem for the annotation of multimedia content that consists of 4 main applications:
- WebLabel Player, for already annotated multimedia content visualization.
- WebLabel Editor, for multimedia content annotation tasks (from scratch or correcting already annotated content).
- WebLabel Manager, for WebLabel user/task managing.
- WebLabel Creator, for WebLabel tasks definition.

WebLabel manages OpenLABEL content using the [Video Content Description (VCD)](https://github.com/Vicomtech/video-content-description-VCD) library.

## OpenLABEL

[ASAM OpenLABEL](https://www.asam.net/standards/detail/openlabel/) defines the annotation format and labeling methods for objects and scenarios. ASAM OpenLABEL provides a guideline on how the labeling methods and definitions should be used.

WebLabel supports (loads, create, visualize) labels compliant with ASAM OpenLABEL 1.0.

## VCD

[Video Content Description](https://github.com/Vicomtech/video-content-description-VCD) is the library which manages OpenLABEL content, with an API that allows creating, modifying, reading and writing labels in OpenLABEL format.

WebLabel uses the [VCD NPM package](https://www.npmjs.com/package/vcd-ts).


<img src="https://raw.githubusercontent.com/Vicomtech/weblabel/main/docs/logo/editor_logo_white.svg" width="300" style="display: block;  margin-left: auto;   margin-right: auto" />

WebLabel Player is a web application to create, edit and visualize annotations (often called labels or tags) in OpenLABEL format.

The application can load JSON files in OpenLABEL format for a wide variety of labeling use cases:

* 2D Bounding boxes in images/videos
* 3D Cuboids in point clouds
* 2D/3D polylines and polygons
* Time-events and actions
* Time-consistent objects (with UID)

<img src="https://raw.githubusercontent.com/Vicomtech/weblabel/main/docs/logo/player_logo_white.svg" width="300" style="display: block;  margin-left: auto;   margin-right: auto" />

<img src="https://raw.githubusercontent.com/Vicomtech/weblabel/main/docs/logo/manager_logo_white.svg" width="300" style="display: block;  margin-left: auto;   margin-right: auto" />

<img src="https://raw.githubusercontent.com/Vicomtech/weblabel/main/docs/logo/creator_logo_white.svg" width="300" style="display: block;  margin-left: auto;   margin-right: auto" />

## Credits

Vicomtech created WebLabel in 2020. Developments of WebLabel were supported and funded by the European Commission (EC) Horizon 2020 programme (project [Cloud-LSVA](http://cloud-lsva.eu), grant agreement 688099).

WebLabel was registered on 24/05/2022 at the "Registro de Propiedad Intelectual" nº 01/2022/786.






