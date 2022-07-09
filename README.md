# FreeCAD alarm clock
This is a FreeCAD project modeling an alarm clock. I have a real alarm clock
on my desk and reproduced it in FreeCAD as an exercise.

Project manifest:
* The FreeCAD files in `/parts`. The top-level assembly is `asm_main.FCStd`.
* An exploded view of the labeled parts.
* The assembly graph with all parts and assemblies.
* Thumbnail views for all the parts and assemblies.
* Photographs of the real alarm clock for reference.

![main_front](https://user-images.githubusercontent.com/48186690/178104948-0f6ef932-53bb-4b8e-9429-a92045edc38c.png)
![main_back](https://user-images.githubusercontent.com/48186690/178104956-65e54fd8-40df-4d71-99fe-0ffe55660aeb.png)

Thumbnails and photographs are included as part of a separate downloadable data
release.

## Parts diagram
The following diagram lists all the parts on an exploded view.

![exploded diagram](doc/exploded_diagram.svg)

The parts are grouped by assemblies according to the following diagram

![assemblies graph](doc/assemblies.svg)

## Animating
The animation of assemblies for the purpose of producing exploded views is
controlled by the variable `explode` in the file `master_animator`.

## Software
I used FreeCAD 0.19.4 for Void Linux 64bits.
The assemblies are made using
[Assembly4](https://github.com/Zolko-123/FreeCAD_Assembly4).

## Limitations
This is my first FreeCAD project, and among my first CAD projects. As such
there are doubtlessly some awkward choices in the design.

* There are warnings that I do not know how to resolve about out-of-scope links.
* Overall I am happy with the design of parts, which is made with sketches in
  the PartDesign workbench. There may be beginner mistakes.

## Illustrations
### Parts and assemblies
`asm_main`
![main_side](https://user-images.githubusercontent.com/48186690/178105035-9fa5e24a-796a-47c9-9716-758c5ff21ec7.png)

`asm_front_shell`
![asm_front_shell](https://user-images.githubusercontent.com/48186690/178105046-f0d15d13-0638-439e-aeca-6a168364a646.png)

`asm_clock_hands`
![asm_clock_hands](https://user-images.githubusercontent.com/48186690/178105063-2c46e710-93c2-4907-8f50-cddc446e4143.png)

`clock_face`
![clock_face](https://user-images.githubusercontent.com/48186690/178105094-eb1f40e4-1e7b-45c4-8ed5-d1312d5b4094.png)

`hand_alarm`
![hand_alarm](https://user-images.githubusercontent.com/48186690/178105122-c02d3a5c-a1b3-4312-9946-31d8de9e00d8.png)

`hand_hour`
![hand_hour](https://user-images.githubusercontent.com/48186690/178105148-c9498ce2-c33b-41b8-93ef-69af1f554a22.png)

`hand_minute`
![hand_minute](https://user-images.githubusercontent.com/48186690/178105150-4e2ef983-bf56-4833-b5c4-907e2ef7f974.png)

`hand_seconds`
![hand_seconds](https://user-images.githubusercontent.com/48186690/178105155-591a0f52-bef7-4ade-9a48-ec45e5f0c453.png)

`shell_front`
![shell_front](https://user-images.githubusercontent.com/48186690/178105167-1e500c29-3553-46c7-a219-c3a5c5f0bf8b.png)

`front_glass`
![front_glass](https://user-images.githubusercontent.com/48186690/178105176-298efa9d-22fc-4daa-8801-e211ee911346.png)

`asm_back_shell`
![asm_back_shell](https://user-images.githubusercontent.com/48186690/178105190-4b693aef-59a5-4ffa-94e7-fe0b9bf6db1d.png)

`shell_back`
![shell_back](https://user-images.githubusercontent.com/48186690/178105198-8c79ede2-7ba2-4714-92ed-f2d82af44a58.png)

`asm_battery_container`
![asm_battery_container](https://user-images.githubusercontent.com/48186690/178105219-f2b49d7f-6e58-4070-b963-729923eb4222.png)

`battery_container`
![battery_container](https://user-images.githubusercontent.com/48186690/178105234-343adffd-7d56-45e4-a111-e08ee397c59f.png)

`battery_contact_minus`
![battery_contact_minus](https://user-images.githubusercontent.com/48186690/178105238-2d51ddae-a969-4865-97a9-b48cd2ae5436.png)

`battery_contact_plus`
![battery_contact_plus](https://user-images.githubusercontent.com/48186690/178105246-fa8c8582-57fd-47b6-9571-f317e3a14210.png)

`battery_aa`
![battery_aa](https://user-images.githubusercontent.com/48186690/178105258-450f8388-1685-442d-a43e-62312ceaad73.png)

`asm_wheel`
![asm_wheel](https://user-images.githubusercontent.com/48186690/178105266-14c5d65c-21b3-4c6a-bd71-bc840ba61310.png)

`wheel`
![wheel](https://user-images.githubusercontent.com/48186690/178105272-092f4fa6-9c4d-435e-bdba-e4ac1106f660.png)

`wheel_axis`
![wheel_axis](https://user-images.githubusercontent.com/48186690/178105276-220c29f3-b1ab-4c06-911c-7a90061f3ca7.png)

`clock_inner`
![clock_inner](https://user-images.githubusercontent.com/48186690/178105284-10942291-3d57-41d6-82bf-31e734e3098f.png)

`alarm_button`
![alarm_button](https://user-images.githubusercontent.com/48186690/178105291-32cce4e9-2193-42e2-9382-077c4b658745.png)

`asm_back_lid`
![asm_back_lid](https://user-images.githubusercontent.com/48186690/178105301-26f6ddcc-8841-4ae1-ba1a-7cde025367fa.png)

`back_lid`
![back_lid](https://user-images.githubusercontent.com/48186690/178105308-f191c09e-8f13-4ed2-b3e2-704136fc5db5.png)

`back_lid_foam`
![back_lid_foam](https://user-images.githubusercontent.com/48186690/178105316-2110a039-41c5-4688-b55f-64b8f13fbc4b.png)

### Photographs
![aa_battery](https://user-images.githubusercontent.com/48186690/178105360-69e6978c-2066-4ea7-be0b-4f5732ea62fd.JPG)
![alarm_button_on](https://user-images.githubusercontent.com/48186690/178105362-a35f5877-c2b9-4437-9d74-240438465cb3.JPG)
![back_lid_back3q](https://user-images.githubusercontent.com/48186690/178105364-2b109ec3-83d2-47a7-bb15-14b1a365b9fd.JPG)
![back_lid_backview](https://user-images.githubusercontent.com/48186690/178105366-3b2bb074-bde3-4759-ad53-774b726fa488.JPG)
![back_lid_inside](https://user-images.githubusercontent.com/48186690/178105367-1ce24bfc-f4a3-4e5e-b2e7-04c5f35663bc.JPG)
![back_lid_sideview](https://user-images.githubusercontent.com/48186690/178105368-ea46eafd-f7d5-4a14-a00b-193d4461f417.JPG)
![back_shell](https://user-images.githubusercontent.com/48186690/178105369-bcb19a6f-8898-4318-ac4e-c15950841ea6.JPG)
![back_shell_3q](https://user-images.githubusercontent.com/48186690/178105370-f654f138-05c4-4870-a602-8a029d6756c6.JPG)
![back_shell_inside](https://user-images.githubusercontent.com/48186690/178105371-e105bacd-130b-4707-af65-fa7bc8d9a766.JPG)
![battery_container_3q](https://user-images.githubusercontent.com/48186690/178105372-8190cbee-7972-4bb5-95e8-a62b44eaf75d.JPG)
![battery_container_front](https://user-images.githubusercontent.com/48186690/178105373-88fe7c33-78a4-44b1-90f8-61545c6decbe.JPG)
![battery_container_full](https://user-images.githubusercontent.com/48186690/178105374-2191089d-a183-4604-901a-7757e069d17b.JPG)
![battery_container_sideview](https://user-images.githubusercontent.com/48186690/178105375-5dfd5664-19a1-49fb-81f2-6843e8946094.JPG)
![battery_container_sideview2](https://user-images.githubusercontent.com/48186690/178105376-4fe33d68-aa1a-47bf-bc7a-64ea798fc7e3.JPG)
![bottom](https://user-images.githubusercontent.com/48186690/178105377-2a229a44-3152-4241-aaa1-4d1a2d1ffc4d.JPG)
![front](https://user-images.githubusercontent.com/48186690/178105378-6a3f2701-a5e8-4ec5-8a8f-5bb719f1ce5a.JPG)
![front_3q](https://user-images.githubusercontent.com/48186690/178105379-a91c10e1-a4b7-4cda-ac84-411b3946f929.JPG)
![hands_detail](https://user-images.githubusercontent.com/48186690/178105380-0caf88a0-5b2a-4532-b2c0-2676ff98684f.JPG)
![left_side](https://user-images.githubusercontent.com/48186690/178105382-c51c1c26-294d-4c76-974f-17df07040e62.JPG)
![presentation](https://user-images.githubusercontent.com/48186690/178105383-f34dda1d-f2be-4b39-9a57-b3fdd7444b81.JPG)
![right_side](https://user-images.githubusercontent.com/48186690/178105384-ea7f9bb7-d157-460b-adaa-2d5c5ebae051.JPG)
![seconds_hand_detail1](https://user-images.githubusercontent.com/48186690/178105385-b4041104-0b96-48db-bafb-5c1dd6994cab.JPG)
![seconds_hand_detail2](https://user-images.githubusercontent.com/48186690/178105386-003c4d5b-a7a4-4528-974e-99cbdaf457cf.JPG)
![top](https://user-images.githubusercontent.com/48186690/178105387-eaac4322-13c0-4d4f-90ac-18bd11b21200.JPG)
![top_3q](https://user-images.githubusercontent.com/48186690/178105389-6d00ec3d-2898-4088-bdc9-604193053b3f.JPG)
![wheel_out](https://user-images.githubusercontent.com/48186690/178105390-4bbace51-4bb2-43ce-8530-2d9468f0d6ae.JPG)
