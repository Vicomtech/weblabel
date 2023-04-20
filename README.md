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
<p align="center">
<em>3D sequence (point cloud + videos) annotation in WebLabel Editor</em>
</p>
<img src="https://raw.githubusercontent.com/Vicomtech/weblabel/main/docs/logo/player_logo_white.svg" width="300" style="display: block;  margin-left: auto;   margin-right: auto" />

WebLabel Player is a similar application to WebLabel Editor, but it only allows visualization of already annotated sequences. It is the ideal application for validation of annotation tasks, whether manual or automatic.


<img src="https://raw.githubusercontent.com/Vicomtech/weblabel/main/docs/logo/manager_logo_white.svg" width="300" style="display: block;  margin-left: auto;   margin-right: auto" />

WebLabel Manager allows a user to orchestrate annotation and supervising tasks for WebLabel Editor and WebLabel Player. Orchestration means creation, assignment and monitoring its status, as well as managing its results. It also gives access to those who have permissions to the WebLabel Creator tool.

A user, when accessing this dashboard-based application, will be allowed to perform see his or her pending tasks or will depending his or her role in the WebLabel annotation ecosystem.

<img src="https://raw.githubusercontent.com/Vicomtech/weblabel/main/docs/logo/creator_logo_white.svg" width="300" style="display: block;  margin-left: auto;   margin-right: auto" />

WebLabel Creator is an ontology-based configuration assistant. The user can load the media (video, image, etc.) that will be labelled in the task and choose the element types to annotate and their attributes. The user can select the relevant properties for the task from the ontology or insert them manually.
The output of WebLabel Creator will be a folder with all the files needed for the annotation task: multimedia content, the configuration file for the application and the initial OpenLabel file.

## Use case

An example of WebLabel Player can be downloaded [HERE](https://github.com/Vicomtech/weblabel/releases/). This release is prepared to load the open dataset created by German Centre for Rail Traffic Research at the Federal Railway Authority (DZSF), Digitale Schiene Deutschland / DB Netz AG, and FusionSystems GmbH. The dataset can be found [HERE](https://doi.org/10.57806/9mv146r0).

## Credits

Vicomtech created WebLabel in 2020. Developments of WebLabel were supported and funded by the European Commission (EC) Horizon 2020 programme (project [Cloud-LSVA](http://cloud-lsva.eu), grant agreement 688099).

WebLabel was registered on 24/05/2022 at the "Registro de Propiedad Intelectual" nº 01/2022/786.

## Copyright

Copyright ©️ 2023 Fundación Centro de Tecnologías de Interacción Visual y Comunicaciones Vicomtech
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), for the use, copy and reproduction of the Software alongside  [the dataset](https://doi.org/10.57806/9mv146r0), subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING OUT OF, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.







