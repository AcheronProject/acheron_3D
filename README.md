# Acheron 3D KiCad footprint library

![alt text](https://raw.githubusercontent.com/Gondolindrim/acheronLibrary/master/graphics/acheronReadme.png "Acheron Logo")

## Introduction

Acheron 3D is the AcheronProject's KiCad footprint 3D models library for. Most of these models were obtained online; check the **Description and credits** section for the due credits.

## How to use

1. Clone the git repository into a ``libraries`` folder inside your KiCad project main folder, also known was ``${KIPRJMOD}``.
2. In PCBNEW, go into ``Preferences > Configure paths... `` then under the ``Environment Variables`` section, add an alias called ``ACHERON_3D`` and set the path to the library you just downloaded.
3. After that the library footprints should be shown with their 3D step models in KiCAD's renders.

## Description and credit


- ``DFN-8`` was obtained from  [3D ContentCentral's website](https://www.3dcontentcentral.com/download-model.aspx?catalogid=171&id=602171) (last accessed july 09, 2021).
- ``QFN-60_7x7mm_P0.4mm`` was copied from [Ultra Librarian's page](https://app.ultralibrarian.com/details/CA8B0F7C-78E3-11EA-8C00-0AD2C9526B44/ISSI/IS31FL3741-QFLS4-TR?ref=digikey) (last access march 25, 2021).
- ``DHN-02F`` was obtained from [3DCC's page](http://https://www.3dcontentcentral.com/download-model.aspx?catalogid=171&id=1024220) (last access july 27, 2021).
- ``811-22-`` are spring-loaded connector pins and their STEP models were optained directly from [Millmax's website](https://www.mill-max.com/) (last access january 21, 2022).
- ``IR12_21C_TR8``, ``PT12_21B_TR8``, ``LKIR30102C_A02`` and ``LKPT30102B_A01`` are STEP/WRL models of IR transmitters and receivers, modelled by Rico of [My Maker Corner](https://github.com/mymakercorner).
- ``BIVAR_LPV2-0450FP`` was obtained directly from [Bivar's website](https://www.bivar.com/product/lpv2-0450fp/) (last access march 28, 2022)
- ``SC70-6`` from [this GrabCAD page](https://grabcad.com/library/sc70-packages-1) (last access january 5, 2022)
- ``mill-max-811-22-00X-30-000101`` were obtained directly from [MillMax's website](https://www.mill-max.com/products/spring-loaded/slc-pin-header-strip/811-xx-xxx-30-000101/811-22-003-30-000101) (last access january 7, 2022)
- ``BMXXB-SRSS-TB.STEP``and ``SMXXB-SHLS-TF.STEP`` were ontained from [JST America's website](https://www.jst.com/) (last access january 7, 2022)
- ``2005280160.stp`` is an EZMate Pico connector was obtained from [MOLEX's website](https://www.molex.com/molex/products/part-detail/ffc_fpc_connectors/2005280160) (last access january 7, 2022)
- ``781710005.stp`` is a clamshell-locl FPC cable and was obtained from [MOLEX's website](https://www.molex.com/molex/products/part-detail/pcb_headers/0781710005)  (last access january 7, 2022)
- ``XFCN_F1004-H-16-20G-R`` is a clamshell-lock FPC cable and its model was designed for Acheron.
- ``WS2812B-4020`` is a 4x2mm version of the WS2812 RGB LED and was obtained from [3D ContentCentral's website](https://www.3dcontentcentral.com/download-model.aspx?catalogid=171&id=1401515)
- ``E73-2G4M08S1C`` is a nRF52840 BL module and was obtained from [GrabDAC's website](https://grabcad.com/library/ebyte-e73-2g4m08s1c-1) (last access march 15, 2024)
- ``JST-S2B-PH-SM4-TB`` is a wire-to-board SMD connector and was obtained from [3D ContentCentral's website](https://www.3dcontentcentral.com/download-model.aspx?catalogid=171&id=817113) (last access march 15, 2024)
- ``X05A20H14G.stp`` is a 14-contact 0.5mm pitch clamshell FPC connector and the model was obtained from [Traceparts](https://www.traceparts.com/en/product/xkb-connectivity-fpc-connector-05mm-flip-type-h-20mm-rear-lock-14p-gold-plating?CatalogPath=TRACEPARTS%3ATP10016001005003&Product=90-10122020-019128&PartNumber=X05A20H14G) (last accessed march 27, 2024)
- ``Crystal_SMD_3P_3213.step`` is a 3-pin crystal oscillator and the model was obtained from [3D ContentCentral](https://www.3dcontentcentral.com/download-model.aspx?catalogid=171&id=943178&partnumber=3P%20SMD)
- ``78170002.stp`` is a 2-pin MOLEX EZ-Mate connector used for (among other things) batteries and the model was obtained from [MOLEX' website](https://www.molex.com/en-us/products/part-detail/781710002) (last accessed march 19, 2025)
- ``Raytac_MDBT50Q`` is a nRF52840 module featherboard. The model ws obtained from [Raytac's website](https://www.raytac.com/document/index.php?index_m_id=12) (last accessed july 7, 2025)
- ``ALPS_SSSS811101`` is a SPDT switch. It was obtained from [brunoeagles repo](https://github.com/brunoeagle/kicad-open-3d) which does not have a license (last accessed july 25, 2025)
- ``K2-1107ST-A4DW-06.STEP'' is a SPST switch. It was obtained from [3D Content Central](https://www.3dcontentcentral.com/Download-Model.aspx?catalogid=171&id=1898108) (last accessed october 30, 2025)

## Copyright notice

This project is released under the Acheron Open-Hardware License V1.4.
