<img src="https://raw.githubusercontent.com/Vicomtech/weblabel/main/docs/logo/main_logo_white.svg" width="300" style="display: block;  margin-left: auto;   margin-right: auto" />

WebLabel is a web ecosystem for the annotation of multimedia content that consists of 4 main applications:
- WebLabel Player, for already annotated multimedia content visualization.
- WebLabel Editor, for multimedia content annotation tasks (from scratch or correcting already annotated content).
- WebLabel Manager, for WebLabel user/task managing.
- WebLabel Creator, for definition of WebLabel annotation tasks.

WebLabel manages OpenLABEL content using the [Video Content Description (VCD)](https://github.com/Vicomtech/video-content-description-VCD) library.

## OpenLABEL

[ASAM OpenLABEL](https://www.asam.net/standards/detail/openlabel/) defines the annotation format and labeling methods for objects and scenarios. ASAM OpenLABEL provides a guideline on how the labeling methods and definitions should be used.

WebLabel supports (loads, create, visualize) labels compliant with ASAM OpenLABEL 1.0.

## VCD

[Video Content Description](https://github.com/Vicomtech/video-content-description-VCD) is the library which manages OpenLABEL content, with an API that allows creating, modifying, reading and writing labels in OpenLABEL format.

WebLabel uses the [VCD NPM package](https://www.npmjs.com/package/vcd-ts).


<img src="https://raw.githubusercontent.com/Vicomtech/weblabel/main/docs/logo/editor_logo_white.svg" width="300" style="display: block;  margin-left: auto;   margin-right: auto" />

WebLabel Editor is a web application to create, edit and visualize annotations (often called labels or tags) in OpenLABEL format.

The application can load JSON files in OpenLABEL format for a wide variety of labeling use cases:

* 2D Bounding boxes in images/videos
* 3D Cuboids and segmentation in point clouds
* 2D/3D points, polylines and polygons
* Time-events and actions
* Time-consistent objects (with UID)
<p align="center">
<img src="https://raw.githubusercontent.com/Vicomtech/weblabel/main/docs/WebLabel-UI.JPG" width="600" style="display: block;  margin-left: auto;   margin-right: auto" />
</p>
<img src="https://raw.githubusercontent.com/Vicomtech/weblabel/main/docs/logo/player_logo_white.svg" width="300" style="display: block;  margin-left: auto;   margin-right: auto" />

WebLabel Player is a similar application to WebLabel Editor, but it only allows visualization of already annotated sequences. It is the ideal application for validation of annotation tasks, whether manual or automatic.

An example of WebLabel Player can be downloaded HERE. This release is prepared to load Deutsche Bahn's open dataset that can be found HERE.


<img src="https://raw.githubusercontent.com/Vicomtech/weblabel/main/docs/logo/manager_logo_white.svg" width="300" style="display: block;  margin-left: auto;   margin-right: auto" />

WebLabel Manager allows a user to orchestrate annotation and supervising tasks for WebLabel Editor and WebLabel Player. Orchestration means creation, assignment and monitoring its status, as well as managing its results. It also gives access to those who have permissions to the WebLabel Creator tool.

A user, when accessing this dashboard-based application, will be allowed to perform see his or her pending tasks or will depending his or her role in the WebLabel annotation ecosystem.

<img src="https://raw.githubusercontent.com/Vicomtech/weblabel/main/docs/logo/creator_logo_white.svg" width="300" style="display: block;  margin-left: auto;   margin-right: auto" />

WebLabel Creator is an ontology-based configuration assistant. The user can load the media (video, image, etc.) that will be labelled in the task and choose the element types to annotate and their attributes. The user can select the relevant properties for the task from the ontology or insert them manually.
The output of WebLabel Creator will be a folder with all the files needed for the annotation task: multimedia content, the configuration file for the application and the initial OpenLabel file.

## Credits

Vicomtech created WebLabel in 2020. Developments of WebLabel were supported and funded by the European Commission (EC) Horizon 2020 programme (project [Cloud-LSVA](http://cloud-lsva.eu), grant agreement 688099).

WebLabel was registered on 24/05/2022 at the "Registro de Propiedad Intelectual" nº 01/2022/786.






