# Ray Tracing in One Weekend

![Render](/assets/images/render.png)

Source code for the short course [Ray Tracing in One Weekend](https://raytracing.github.io/books/RayTracingInOneWeekend.html).

### Building

```
sudo apt install ninja-build
pip install -re requirements.txt

meson setup build
cd build
ninja
```

### Running the code and viewing the result

```
./main > render.ppm
eog render.ppm
```
