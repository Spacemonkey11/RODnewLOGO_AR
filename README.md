<script src="https://aframe.io/releases/0.9.0/aframe.min.js"></script>
<script src="https://cdn.rawgit.com/jeromeetienne/AR.js/1.6.2/aframe/build/aframe-ar.js"></script>
<body style='margin : 0px; overflow: hidden;'>
    <a-scene embedded arjs='sourceType: webcam; debugUIEnabled: false;'>
      <a-marker preset='custom' type='pattern' url='https://raw.githubusercontent.com/Spacemonkey11/Spacemonkey11.github.io/master/pattern-RODlogoAR.patt'>
        <a-gltf-model src="https://raw.githubusercontent.com/Spacemonkey11/Spacemonkey11.github.io/master/SubSktchFabwFish.obj/scene.gltf" scale="0.02 0.02 0.02">
        </a-gltf-model>
      </a-marker>
        
      <a-entity camera></a-entity>
    </a-scene>
</body>
