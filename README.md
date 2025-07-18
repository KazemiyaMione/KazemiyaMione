for freelance work? do reach, [email](BronyaMatrix@outlook.com) :)

📊 **this week i spent my time on:**
<!--START_SECTION:waka-->

```txt
TypeScript   15 hrs 28 mins  █████████████████████████   99.70 %
JSON         2 mins          ░░░░░░░░░░░░░░░░░░░░░░░░░   00.30 %
```

<!--END_SECTION:waka-->

if you like what i do, maybe consider buying me a coffee/tea 🥺👉👈

<a href="https://www.buymeacoffee.com/KazemiyaMione" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-red.png" alt="Buy Me A Coffee" width="150" ></a>

🚧 **my todoist stats:**
<!-- TODO-IST:START -->
🏆  8,004 Karma Points           
🌸  Completed 0 tasks today           
✅  Completed 673 tasks so far           
⏳  Longest streak is 10 days
<!-- TODO-IST:END -->


📈 my github stats

<p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=KazemiyaMione&show_icons=true&theme=gotham" alt="abhisheknaiidu" />



<div id="3d-vis" style="width: 100%; height: 300px;"></div>
<script src="https://cdn.jsdelivr.net/npm/three@0.152.2/build/three.min.js"></script>
<script>
  const scene = new THREE.Scene();
  const camera = new THREE.PerspectiveCamera(75, window.innerWidth/window.innerHeight, 0.1, 1000);
  const renderer = new THREE.WebGLRenderer({antialias: true});
  renderer.setSize(window.innerWidth, 300);
  document.getElementById('3d-vis').appendChild(renderer.domElement);

  const geometry = new THREE.BoxGeometry();
  const material = new THREE.MeshNormalMaterial();
  const cube = new THREE.Mesh(geometry, material);
  scene.add(cube);

  camera.position.z = 5;

  function animate() {
    requestAnimationFrame(animate);
    cube.rotation.x += 0.01;
    cube.rotation.y += 0.01;
    renderer.render(scene, camera);
  }
  animate();
</script>
