# Prospector PCB 組み立て手順（暫定版）

## ポゴピンの取り付け
PCBにバッテリー＋パッド用ポゴピンを取り付けます。取り付け位置はコネクタ類とは反対側です。  
マスキングテープなどで固定してから、裏側からはんだをしっかり流し込みます。

## マイコンの取り付け
XIAO nrf52840の背面のバッテリー用マイナスのパッドをショート防止のため絶縁テープ等を貼っておきます。  
ポゴピン設置側にコンスルーを取り付け、その後マイコンを取り付けます。

## コネクタケーブルの取り付け
LCD、センサー、バッテリーのコネクタケーブルを取り付けます。  
センサーのケーブルはコンスルーの飛び出ているピンとやや干渉するため、少し浮かせて差し込みます。  
コンスルーは指に強く当たるとケガをするので気を付けてください。

## ケースの組み立て
オリジナルのケース組み立て手順と同様に、LCDマウント、メインケースと共締めするようにm2x6ネジでLCDを4か所固定します。   
センサーカバーをメインケースの上部の穴にはめ込み、抑えながらセンサーをm2.5x4ネジで2か所取り付けます。  
PCBのスライドスイッチにスライドスイッチカバーを取り付けます。  
リアケースの下部の穴に、リセットスイッチを内側から差し込みます。  
リアケースにマイコンのUSBとスライドスイッチの位置に気を付けながら差し込みます。  
m2x4ネジでPCBを4か所ねじ止めします。  
最後にリアケースをm2.5x4ネジで2か所止めれば完成です。

---
# Prospector Case for PCB

Modified 3D printable case for the Prospector ZMK status display device.

## Attribution

This work is a modification of the original Prospector hardware design:

- **Original Project**: [prospector](https://github.com/carrefinho/prospector) by carrefinho
- **Original License**: CERN Open Hardware Licence Version 2 - Permissive (CERN-OHL-P)

## Modifications

Modified by t-ogura (2026):

1. **PCB Case Adjustments** - Adapted case dimensions to accommodate PCB-based assembly
2. **Power Switch Addition** - Added mounting for slide power switch
3. **Reset Switch Improvement** - Redesigned reset switch holder to prevent breakage
4. **Hexagonal Screw Inserts** - Changed screw holes to hexagonal shape to prevent insert pull-out

## 3D Model Files

| File | Description |
|------|-------------|
| `prospector_main_case.stl` | Main enclosure body |
| `prospector_rear_case.stl` | Rear cover |
| `prospector_lcd_mount.stl` | LCD display mounting frame |
| `prospector_slide_switch.stl` | Power switch holder |
| `prospector_reset_switch.stl` | Reset button holder |
| `prospector_sensor_cover.stl` | Ambient light sensor cover |

## License

This modified work is licensed under the **CERN Open Hardware Licence Version 2 - Permissive (CERN-OHL-P)**.

See the [LICENSE](LICENSE) file for the full license text.

### License Summary

You are free to:
- Use, study, modify, and share this hardware design
- Make and distribute products based on this design
- Use this design for commercial purposes

Under the following conditions:
- Retain all copyright and license notices
- Include a notice stating you have modified the design (if applicable)
