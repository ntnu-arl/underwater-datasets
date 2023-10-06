# Multi Camera Underwater Visual Interial Dataset

This is an underwater dataset collected using an custom BlueROV (Retrofit Heavy Configuration). 

## Trajectories with Visual Inetrial Data
The first subset contains 24 trajectories with 4 motion patterns and varying illumination.

Each of the trajectory contains following data:

* Cameras (cam0, cam1, ... cam 4) (20Hz)
* IMU synced with Camera (200Hz)
* IMU on FCU
* Pressure sensor for depth
* mavros rc/out (ch 1-8 thrusters, ch 9-10 for Lumen LED PWD Value)

The collective data can be found [(1-18)](https://ntnu.box.com/s/xgsepbu96ty8ylzcz7sjyg6vvo3hciwe) and [(19-24)](https://ntnu.box.com/s/xgsepbu96ty8ylzcz7sjyg6vvo3hciwe), whereas the following table contains link to each trajectory:

#### Motion Pattern 1 (Rectangular)
| Trajectory | Illumination | Duration (s) | Size (Gb) | Link | 
| --- | --- | --- | --- | --- |
| 1 | E0+O1 | 460  | 18.1| [link](https://ntnu.box.com/s/nnktnmgshz3e1v6whs6iabfpfubh1j0r)
| 2 | E0+O2 | 456 | 17.8| [link](https://ntnu.box.com/s/150bajeprv0f8jvtk3zwaia3wskpf0u8)
| 3 | E0+O3 | 392 | 15.3| [link](https://ntnu.box.com/s/yldexh6sw50z8oqigy8hrll43kwx754k)
| 4 | E1+O3 | 386 | 15.1| [link](https://ntnu.box.com/s/k7cf5wm2xudpeaecr9xyf6ii40l70dzq)
| 5 | E1+O2 | 443 | 17.3| [link](https://ntnu.box.com/s/7a05kvmw95l0124tsl8zf98egj4wclxc)
| 6 | E1+O3 | 395 | 15.4 | [link](https://ntnu.box.com/s/ru33adfwicobv0ugnpn4byigdfbjho55)

#### Motion Pattern 2 (Hour Glass)
| Trajectory | Illumination | Duration (s) | Size (Gb) | Link | 
| --- | --- | --- | --- | --- |
| 7 | E1+O3 | 460  | 18.1| [link](https://ntnu.box.com/s/2me1s6o4uqzfz3ai804t4sbwvmnzye91)
| 8 | E1+O2 | 456 | 17.8| [link](https://ntnu.box.com/s/2njbkv6mgqzlrxw2vr1k9qkedggd5sdh)
| 9 | E1+O1 | 392 | 15.3| [link](https://ntnu.box.com/s/3vofmpx83jn10jby7om44reapjbculme)
| 10 | E1+O1 | 386 | 15.1| [link](https://ntnu.box.com/s/ow0yjer634yb6y2vibi0f6im6lr3hb2b)
| 11 | E1+O2 | 443 | 17.3| [link](https://ntnu.box.com/s/2nu1q2t6i402j0vt6r9p1280071w0rtb)
| 12 | E1+O3 | 395 | 15.4 | [link](https://ntnu.box.com/s/ybxfvueawqagv20huehqj08gtpxsprwk)

*Note: Two more motion patterns will be updates soon.*

<!-- #### Motion Pattern 3 (Strched Hour Glass)
| Trajectory | Illumination | Duration (s) | Size (Gb) | Link | 
| --- | --- | --- | --- | --- |
| 13 | E1+O3 | 460  | 18.1| [link](https://ntnu.box.com/s/ho8sz412taqe94ehhbmw1icgamh3anu1)
| 14 | E1+O2 | 456 | 17.8| [link](https://ntnu.box.com/s/jbxqb5d9ao9trlsuixciaoer48g8mddh)
| 15 | E1+O1 | 392 | 15.3| [link](https://ntnu.box.com/s/hs9che0xplz1zaqk9vt2xxzi4ux070mz)
| 16 | E0+O1 | 386 | 15.1| [link](https://ntnu.box.com/s/w5948mujkpxq32k3oly5ktuh5oa393up)
| 17 | E0+O2 | 443 | 17.3| [link](https://ntnu.box.com/s/txkgl98rngbm3twv2ifl8lm0ogzoc7mo)
| 18 | E0+O3 | 395 | 15.4 | [link](https://ntnu.box.com/s/ksrjxwbn3iadx0secif8ywgbyphud9a1) -->

<!-- #### Motion Pattern 2 (Strched Hour Glass with Transverse Motion)
| Trajectory | Illumination | Duration (s) | Size (Gb) | Link | 
| --- | --- | --- | --- | --- |
| 1 | External+Level1 | 460  | 18.1| [link](https://ntnu.box.com/s/nnktnmgshz3e1v6whs6iabfpfubh1j0r)
| 2 | External+Level1 | 456 | 17.8| [link](https://ntnu.box.com/s/150bajeprv0f8jvtk3zwaia3wskpf0u8)
| 3 | External+Level1 | 392 | 15.3| [link](https://ntnu.box.com/s/yldexh6sw50z8oqigy8hrll43kwx754k)
| 4 | External+Level1 | 386 | 15.1| [link](https://ntnu.box.com/s/k7cf5wm2xudpeaecr9xyf6ii40l70dzq)
| 5 | External+Level1 | 443 | 17.3| [link](https://ntnu.box.com/s/7a05kvmw95l0124tsl8zf98egj4wclxc)
| 6 | External+Level1 | 395 | 15.4 | [link](https://ntnu.box.com/s/ru33adfwicobv0ugnpn4byigdfbjho55) -->

External light has two levels E0 corresponding to 100 - 300 lux and E1 corresponding to 400-700 lux measured outside and above water surface.

### Trajectories with Varying Media (Air, Water)
The second subset contains 6 trajectories with varying media (Air, Water).

| Trajectory | Duration | Size | Link | 
| --- | --- | --- | --- |
| 1 |  173  | 2.6| [link](https://ntnu.box.com/s/iwx42iv4hunvc74zy2s3du6g7nhe1ja4)
| 2 |  126 | 1.9| [link](https://ntnu.box.com/s/57c4pxgxms20ok4l6hvoxbrvfdlj26h1)

### Visual Inertial Calibration 

The cameras were calibrated using the [Kalibr](https://github.com/ethz-asl/kalibr) toolbox. The calibration data can be found in the folder `calibration_data` and following table contains the links for each camera intrinsics and extrinsics.

| Camera | Intrinsics (Air) | Intrinsics (Water) | Extrinsics | 
| --- | --- | --- | --- |
| cam0, cam1(Stereo Pair)| [link](https://ntnu.box.com/s/rwzq02hu1bfqxfy42bub543bxqyrq4sm) | [link](https://ntnu.box.com/s/2a8avom1h12wuzqbhonigqqa7rbe0g73) | [link](https://ntnu.box.com/s/whcuhsbetjoxgwsh4hw5lx14gqdnd7bl)
| cam3| [link]() | [link](https://ntnu.box.com/s/2a8avom1h12wuzqbhonigqqa7rbe0g73) | [link](https://ntnu.box.com/s/whcuhsbetjoxgwsh4hw5lx14gqdnd7bl)
| cam4| [link]() | [link](https://ntnu.box.com/s/2a8avom1h12wuzqbhonigqqa7rbe0g73) | [link](https://ntnu.box.com/s/whcuhsbetjoxgwsh4hw5lx14gqdnd7bl)