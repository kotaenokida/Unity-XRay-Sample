# Kudan Unity X-Ray Sample

The Unity X-Ray Sample uses a stencil buffer, along with some alpha transparency, to achieve occlusion. The buffer makes a portal effect, making the contents of the box only visible through its lid. Place the marker flat on top of a box and give it a try. This is only used with marker tracking in our sample.

The “Hidden” shader is the one that should be applied to any object you don’t want to view, except through a specific object. The “Portal” object should be applied to the object you want to view hidden objects through.

## Instructions
- Download the Kudan Unity Plugin from [the XLsoft Kudan Download Page](https://www.xlsoft.com/en/products/kudan/download.html).
- Open the Unity Project and go to **Assets -> Import Package -> Custom Package**
- Add `KudanARUnity.unitypackage`
- Build and run the Unity Project

For any additional questions or concerns, visit the [XLsoft Kudan Developer Hub](https://www.xlsoft.com/doc/kudan/).

For any inquires, please contact [XLsoft](https://www.xlsoft.com/en/services/xl_form.html).
