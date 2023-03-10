# SturdyBunny
Mechanical modifications for ERCF MMU to improve robustness and repeatability

# Motivation

It is also important to understand why these changes were made. At a high level, the main reason these changes were made at all can be summarised as follows:

- The entire ERCF assembly is not very rigid when fully assembled, especially with high filament block numbers (>6). In my first built, picking up the ERCF caused the weight of the assembly to be supported entirely by the main drive D shaft - causeing a slight bend. It seems that it is intended that whatever the ERCF is mounted to should provide sufficient rigidty to the entire assembly.
- The three nubs the key the filament blocks together were not particularly effective in my build, and a small amount of rotation was permissible. This didnt give me confidence that the assembly was rigid to ensure repeatibility during filament loading/unloading - something I was never able to achieve during my 'stock' build.
- I found that using threaded rods to hold the whole assembly together was very prone to user error. Ovetightening damaged the parts, and undertightening made the entire assembly even looser.

# Goals

For the reasons stated above, I believe that a few modifications can be made to vastly improve the robustness of the ERCF design. Doing so should reduce t

My goals with this project can be summarised below:
- maintain the original design intent with how the ERCF is supposed to function. The overall concept of the ERCF is great and I am yet to see a reason to change that.
- Improve the robustness by making the ERCF assembly **self-supporting,** so that it does not require an external frame/mount for rigidty.
- Reduce the opportunity for user error during assembly.
- Improve repeatability of the system during filament loading/unloading.


# Overall design change summary

The changes to the design can be summarised as followed:
- The gearbox, hinge and filament blocks are all secured to a 2020 aluminium extrusion, independent from eachother. This significantly improves the robuseness of the assembly, and is much more accomodating to printer calibration.


# Gallery

<img width="751" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/219339445-99551fb0-b9c3-44d8-9530-d1575f7b84d0.png">

<img width="751" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/219339421-af12978a-4316-4073-a3a8-409226749ea3.png">

# Project Status

- Proof of concept is working, and I am currently using it.
- Some of the changes reduce the printability of some parts, and thus require lots of supports. If there is sufficient interest in this project from the community, I intend to revisit these parts to improve their printability.


