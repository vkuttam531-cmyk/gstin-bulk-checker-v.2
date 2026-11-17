# GSTIN Bulk Checker

A Chrome / Edge extension that looks up the public details of GSTINs on the GST portal and fills them into your **Excel (.xlsx) or CSV** file.

> Unofficial tool. It is not affiliated with GSTN or the Government of India. It does not bypass or solve captchas.

## What you get
Legal Name, Trade Name, Status, Registration Date, Cancellation Date, Principal Place of Business, Offices, HSN / HSN Description.

## Download
Open the **Releases** page of this repository and download:
- `gstin-bulk-checker-extension.zip` - the extension
- `gstin-bulk-checker-excel-addin.zip` - optional Excel add-in (Windows desktop Excel only)

## Install the extension
1. Extract `gstin-bulk-checker-extension.zip` into a **permanent folder** (for example `C:\GSTExtension`). Do not delete or move it afterwards.
2. Open `chrome://extensions` (Edge: `edge://extensions`) and turn on **Developer mode**.
3. Click **Load unpacked** and choose the extracted folder.
4. Open the GST portal **Search Taxpayer** page. The panel appears on the right.

To update later, replace the files in the same folder and click **Reload** on the extension. Do not remove the extension or load it again from another folder - that resets your Device ID.

## License
A license key is required. For a key, contact **vkuttam531@gmail.com**.

No internet access to the license server? The panel shows your **Device ID**. Send it to the contact above and you will receive a license code that works offline for a limited period. Paste the key or code into the **License key** box at the top of the panel.

## Use
1. Enter your license key.
2. Upload your Excel/CSV file (**Upload your file**) or paste GSTINs.
3. **Mode A:** type the captcha yourself. **Mode B:** log in to the GST portal yourself first, search one GSTIN manually, then press Start.
4. Press **Start**. When it finishes, press **Download** to get the filled file.

## Excel add-in (optional)
Adds a floating **Get Data** window to Excel that fills results into your open sheet as they arrive. See `SETUP.md` inside the add-in zip.

## Privacy
Privacy policy: https://YOUR-GITHUB-USERNAME.github.io/gstin-bulk-checker/
