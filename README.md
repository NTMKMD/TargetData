# TargetData

本リポジトリは，「ファジングを用いたSBFLにおける疑惑値算出式の比較調査」における各不具合の修正箇所および初期シードの詳細を掲載している．

## 修正箇所

<table>
  <tr>
    <th>ソフトウェア</th>
    <th>バグID</th>
    <th>修正ファイル</th>
    <th>修正行</th>
  </tr>
  <tr>
    <td rowspan="4">lua</td>
    <td>lua-1</td>
    <td>ldo.c</td>
    <td>415</td>
  </tr>
  <tr>
    <td>lua-2</td>
    <td>ldo.c</td>
    <td>536</td>
  </tr>
  <tr>
    <td>lua-3</td>
    <td>ltable.c</td>
    <td>154, 155, 156, 157, 164, 694</td>
  </tr>
  <tr>
    <td>lua-4</td>
    <td>lvm.c</td>
    <td>1131</td>
  </tr>
  <tr>
    <td rowspan="2">bluez</td>
    <td>bluez-1</td>
    <td>sdp-xml.c</td>
    <td>548</td>
  </tr>
  <tr>
    <td>bluez-2</td>
    <td>textfile.c</td>
    <td>130, 131, 132, 133</td>
  </tr>
  <tr>
    <td>hdf5</td>
    <td>hdf5-1</td>
    <td>H5Ofsinfo.c</td>
    <td>97, 98, 99, 100, 101, 117, 132, 146, 205</td>
  </tr>
  <tr>
    <td>inchi</td>
    <td>inchi-1</td>
    <td>inchi_dll.c</td>
    <td>3344</td>
  </tr>
  <tr>
    <td rowspan="2">plan9port</td>
    <td>plan9port-1</td>
    <td>x509.c</td>
    <td>2524, 2528, 2535</td>
  </tr>
  <tr>
    <td>plan9port-2</td>
    <td>x509.c</td>
    <td>683</td>
  </tr>
  <tr>
    <td>librope</td>
    <td>librope-1</td>
    <td>rope.c</td>
    <td>187, 431, 443, 543, 555</td>
  </tr>
  <tr>
    <td>binutils</td>
    <td>binutils-1</td>
    <td>obj-elf.c</td>
    <td>1952, 1964, 2006</td>
  </tr>
  <tr>
    <td>gdbm</td>
    <td>gdbm-1</td>
    <td>gdbmload.c</td>
    <td>77, 87, 125, 154, 161, 226</td>
  </tr>
</table>

## 初期シード

`seed/` フォルダに各不具合の初期シードを格納している．
