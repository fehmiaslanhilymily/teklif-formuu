<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SUR YOL TEKNOLOJİ - Teklif Oluşturucu</title>
    <style>
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: Arial, Helvetica, sans-serif; }
        body { background-color: #f3f4f6; padding: 20px; color: #000; }
        .app-container { max-width: 1100px; margin: 0 auto; display: flex; gap: 20px; flex-wrap: wrap; }
        .editor-panel { flex: 1; min-width: 320px; background: #fff; padding: 20px; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); }
        .preview-panel { flex: 1.4; min-width: 340px; background: #fff; padding: 20px; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); overflow-x: auto; }
        h2 { font-size: 18px; margin-bottom: 15px; border-bottom: 2px solid #e5e7eb; padding-bottom: 8px; color: #1f2937; }
        .form-group { margin-bottom: 12px; }
        .form-group label { display: block; font-size: 12px; font-weight: bold; margin-bottom: 4px; color: #374151; }
        .form-group input, .form-group select { width: 100%; padding: 8px; border: 1px solid #d1d5db; border-radius: 4px; font-size: 13px; }
        .form-row { display: flex; gap: 10px; }
        .btn { padding: 10px 16px; border: none; border-radius: 4px; font-weight: bold; cursor: pointer; font-size: 13px; display: inline-flex; align-items: center; justify-content: center; gap: 6px; transition: 0.2s; }
        .btn-primary { background-color: #2563eb; color: #fff; }
        .btn-primary:hover { background-color: #1d4ed8; }
        .btn-success { background-color: #16a34a; color: #fff; }
        .btn-success:hover { background-color: #15803d; }
        .btn-danger { background-color: #dc2626; color: #fff; padding: 4px 8px; font-size: 11px; }
        .btn-danger:hover { background-color: #b91c1c; }
        .action-buttons { display: flex; gap: 10px; margin-bottom: 20px; }
        
        /* A4 Teklif Formu Tasarımı (Birebir İlgili Görsele Sadık) */
        .paper { width: 210mm; min-height: 297mm; padding: 12mm 15mm; margin: 0 auto; background: #fff; box-shadow: 0 0 10px rgba(0,0,0,0.15); box-sizing: border-box; font-size: 11px; line-height: 1.2; position: relative; }
        
        .top-amber-bar { height: 16px; background-color: #f59e0b; width: 100%; margin-bottom: 8px; }
        .header-table { width: 100%; border-collapse: collapse; margin-bottom: 6px; }
        .header-table td { vertical-align: top; }
        
        /* Orijinal Vektörel Logo */
        .logo-box { display: flex; align-items: center; gap: 6px; }
        .logo-orange { width: 16px; height: 38px; background-color: #e65100; }
        .logo-blue { width: 16px; height: 38px; background-color: #0277bd; }
        .logo-arrow { width: 0; height: 0; border-top: 19px solid transparent; border-bottom: 19px solid transparent; border-left: 20px solid #0277bd; }
        .logo-text { font-family: 'Arial Black', Gadget, sans-serif; font-weight: 900; font-size: 20px; color: #1a237e; letter-spacing: -0.5px; line-height: 1; }
        .logo-subtext { font-size: 10px; color: #757575; letter-spacing: 0.5px; font-weight: bold; margin-top: 2px; }

        .company-info { text-align: right; font-size: 9.5px; font-weight: bold; }
        .company-name { font-size: 10.5px; font-weight: 900; color: #000; }
        
        .thick-divider { height: 4px; background-color: #000; margin: 6px 0; }
        
        .grid-table { width: 100%; border-collapse: collapse; margin-bottom: -1px; }
        .grid-table th, .grid-table td { border: 1px solid #000; padding: 3px 5px; font-size: 10px; }
        .grid-table th { background-color: #e5e7eb; font-weight: bold; text-align: center; }
        
        .text-center { text-align: center; }
        .text-right { text-align: right; }
        .font-bold { font-weight: bold; }
        .italic { font-style: italic; }

        /* Vurgulu Toplam Satırları */
        .bg-yellow { background-color: #fef08a !important; font-weight: bold; }
        .bg-green { background-color: #bbf7d0 !important; font-weight: bold; }
        .bg-red { background-color: #ff0000 !important; color: #fff !important; font-weight: bold; text-align: center; }
        
        .arrow-indicator { display: inline-block; width: 0; height: 0; border-top: 5px solid transparent; border-bottom: 5px solid transparent; border-right: 7px solid #000; margin-right: 4px; }
        
        .product-table { width: 100%; border-collapse: collapse; }
        .product-table th, .product-table td { border: 1px solid #000; padding: 2.5px 4px; font-size: 9.5px; }
        .product-table th { background-color: #e5e7eb; font-style: italic; font-weight: bold; }
        
        .totals-table { width: 45%; margin-left: auto; border-collapse: collapse; margin-top: -1px; }
        .totals-table td { border: 1px solid #000; padding: 2.5px 5px; font-size: 9.5px; }

        .notes-list { list-style: none; padding-left: 0; margin-top: 6px; font-size: 8.5px; font-style: italic; }
        .notes-list li { margin-bottom: 2px; }
        .notes-list li::before { content: "* "; font-weight: bold; }

        .signatures-table { width: 100%; border-collapse: collapse; margin-top: 15px; }
        .signatures-table td { width: 50%; vertical-align: top; }
        .sig-box { width: 80%; border: 2px solid #000; height: 35px; margin-top: 4px; }

        .footer-logo { margin-top: 25px; display: flex; align-items: center; gap: 5px; }
        .footer-logo .logo-orange { height: 26px; width: 11px; }
        .footer-logo .logo-blue { height: 26px; width: 11px; }
        .footer-logo .logo-arrow { border-top: 13px solid transparent; border-bottom: 13px solid transparent; border-left: 14px solid #0277bd; }
        .footer-logo .logo-text { font-size: 14px; }
        .footer-logo .logo-subtext { font-size: 7.5px; }

        /* Yazdırma / PDF İçin Özel Kurallar */
        @media print {
            body { background: none; padding: 0; }
            .editor-panel, .action-buttons { display: none !important; }
            .preview-panel { padding: 0; box-shadow: none; background: none; flex: none; width: 100%; }
            .paper { box-shadow: none; margin: 0; padding: 8mm 10mm; width: 100%; page-break-after: always; }
            @page { size: A4 portrait; margin: 0; }
        }
    </style>
</head>
<body>

<div class="app-container">
    <!-- SOL TARAFTAKİ FORM PANELİ -->
    <div class="editor-panel">
        <h2>Teklif Bilgileri Girişi</h2>
        
        <div class="form-row">
            <div class="form-group" style="flex: 1;">
                <label>Tarih</label>
                <input type="text" id="inpTarih" value="28.10.2026" oninput="updateForm()">
            </div>
            <div class="form-group" style="flex: 2;">
                <label>Alıcı Firma</label>
                <input type="text" id="inpAliciFirma" value="" placeholder="Firma Adı" oninput="updateForm()">
            </div>
        </div>

        <div class="form-row">
            <div class="form-group" style="flex: 1;">
                <label>Yetkili</label>
                <input type="text" id="inpYetkili" value="Fehmi Aslan" oninput="updateForm()">
            </div>
            <div class="form-group" style="flex: 1;">
                <label>Yetkili Telefonu</label>
                <input type="text" id="inpTelefon" value="" oninput="updateForm()">
            </div>
        </div>

        <div class="form-row">
            <div class="form-group" style="flex: 1;">
                <label>Teslim Yeri</label>
                <input type="text" id="inpTeslimYeri" value="" oninput="updateForm()">
            </div>
            <div class="form-group" style="flex: 1;">
                <label>Ödeme Yapılacak Tarih</label>
                <input type="text" id="inpOdemeTarihi" value="" oninput="updateForm()">
            </div>
        </div>

        <div class="form-group">
            <label>İlgili Satış Sorumlusu</label>
            <input type="text" id="inpSatisSorumlusu" value="" oninput="updateForm()">
        </div>

        <h2 style="margin-top: 15px;">Ürün / Hizmet Kalemleri</h2>
        
        <div id="itemsContainer"></div>

        <button class="btn btn-primary" onclick="addItem()" style="width: 100%; margin-top: 8px;">+ Yeni Ürün Ekle</button>
    </div>

    <!-- SAĞ TARAFTAKİ ÖNİZLEME PANELİ -->
    <div class="preview-panel">
        <div class="action-buttons">
            <button class="btn btn-success" onclick="downloadPDF()">📄 PDF Olarak İndir</button>
            <button class="btn btn-primary" onclick="downloadExcel()">📊 Excel (.xls) Olarak İndir</button>
        </div>

        <!-- A4 FORMU -->
        <div class="paper" id="invoicePaper">
            <div class="top-amber-bar"></div>
            
            <table class="header-table">
                <tr>
                    <td style="width: 50%;">
                        <div class="logo-box">
                            <div class="logo-orange"></div>
                            <div class="logo-blue"></div>
                            <div class="logo-arrow"></div>
                            <div style="margin-left: 4px;">
                                <div class="logo-text">SUR YOL</div>
                                <div class="logo-subtext">TEKNOLOJİ PAZARLAMA</div>
                            </div>
                        </div>
                    </td>
                    <td style="width: 50%;">
                        <div class="company-info">
                            <div class="company-name">SUR YOL TEKNOLOJİ PAZARLAMA SANAYİ TİCARET LİMİTED ŞİRKETİ</div>
                            <div class="italic">Sinan Paşa Mah. Süleyman Seba Caddesi No:6 İçkapı:4 / Beşiktaş, İSTANBUL – Türkiye</div>
                            <div class="italic">E-posta: muhasebe@hilymily.com | Vergi No: 7840728513 (BEŞİKTAŞ)</div>
                        </div>
                    </td>
                </tr>
            </table>

            <div class="thick-divider"></div>

            <table class="grid-table">
                <tr>
                    <td style="width: 70%;" class="text-center font-bold">ALICI FİRMA</td>
                    <td style="width: 15%;" class="text-center font-bold">TARİH</td>
                    <td style="width: 15%;" class="text-center font-bold" id="lblTarih">28.10.2026</td>
                </tr>
            </table>

            <table class="grid-table">
                <tr>
                    <td style="width: 30%;" class="italic">Yetkili</td>
                    <td style="width: 70%;" id="lblYetkili">Fehmi Aslan</td>
                </tr>
                <tr>
                    <td class="italic">Yetkili Telefonu</td>
                    <td id="lblTelefon"></td>
                </tr>
                <tr>
                    <td class="italic">Teslim Yeri</td>
                    <td id="lblTeslimYeri"></td>
                </tr>
                <tr>
                    <td class="italic">Ödeme Yapılacak Tarih</td>
                    <td id="lblOdemeTarihi"></td>
                </tr>
                <tr>
                    <td class="italic">İlgili Satış Sorumlusu</td>
                    <td id="lblSatisSorumlusu"></td>
                </tr>
                <tr>
                    <td class="text-center font-bold" style="vertical-align: middle;">BANKA İBAN BİLGİLERİ</td>
                    <td class="text-center font-bold">
                        VAKIF BANK / İMSAN ŞUBESİ<br>
                        TR94 0001 5001 5800 7322 6926 65
                    </td>
                </tr>
            </table>

            <table class="product-table" style="margin-top: 1px;">
                <thead>
                    <tr>
                        <th style="width: 4%;">No</th>
                        <th style="width: 48%;">ÜRÜN AÇIKLAMASI</th>
                        <th style="width: 14%;">miktar / birim</th>
                        <th style="width: 11%;">kdv dahil<br>birim fiyat TL</th>
                        <th style="width: 10%;">Kdv</th>
                        <th style="width: 13%;">kdv dahil toplam</th>
                    </tr>
                </thead>
                <tbody id="productRows">
                    <!-- Ürünler buraya eklenecek -->
                </tbody>
            </table>

            <table class="totals-table">
                <tr>
                    <td style="width: 60%;" class="text-right font-bold">TOPLAM</td>
                    <td style="width: 40%;" class="text-right font-bold" id="lblMatrah">0,00</td>
                </tr>
                <tr>
                    <td class="text-right font-bold">%20 KDV</td>
                    <td class="text-right font-bold">%20 KDV</td>
                </tr>
                <tr>
                    <td class="text-right font-bold">KDV</td>
                    <td class="text-right font-bold" id="lblKdvTutar">0,00</td>
                </tr>
                <tr class="bg-yellow">
                    <td class="text-right"><span class="arrow-indicator"></span>TUTAR</td>
                    <td class="text-right" id="lblGenelToplam">0,00</td>
                </tr>
                <tr class="bg-green">
                    <td class="text-right"><span class="arrow-indicator"></span>SİPARİŞ ORTALAMA VADE</td>
                    <td class="text-right"></td>
                </tr>
            </table>

            <table class="grid-table" style="margin-top: 8px;">
                <tr>
                    <td class="text-center font-bold">ARAÇTA KG BAZINDA OLANLARDA DEĞİŞİKLİK OLABİLİR.</td>
                </tr>
                <tr>
                    <td class="bg-red">SADECE NAKİT FİYATIDIR</td>
                </tr>
            </table>

            <ul class="notes-list">
                <li>Üstte talep etmiş olduğunuz ürün sipariş onayınıza istinaden geçerlidir.</li>
                <li>Onay verilen siparişlerde para iadesi söz konusu olamaz.</li>
                <li>Teklif geçerlilik tarihi bugün saat 17:00 dir.</li>
            </ul>

            <table class="signatures-table">
                <tr>
                    <td style="padding-left: 20px;">
                        <div class="italic font-bold" style="font-size: 9px;">SATICI ONAYI</div>
                        <div class="sig-box"></div>
                    </td>
                    <td style="padding-left: 40px;">
                        <div class="italic font-bold" style="font-size: 9px; text-align: right; width: 80%;">ALICI ONAYI</div>
                        <div class="sig-box" style="margin-left: auto;"></div>
                    </td>
                </tr>
            </table>

            <div class="footer-logo">
                <div class="logo-orange"></div>
                <div class="logo-blue"></div>
                <div class="logo-arrow"></div>
                <div style="margin-left: 3px;">
                    <div class="logo-text">SUR YOL</div>
                    <div class="logo-subtext">TEKNOLOJİ PAZARLAMA</div>
                </div>
            </div>
        </div>
    </div>
</div>

<script>
    let items = [
        { desc: "FAWORİ OPTİMİX 5 CM 16 DNS MANTOLAMA TAKIM BOYA ASTAR HARİÇ", qty: 7, unit: "M2", price: 390.50 }
    ];

    function fmt(val) {
        if (isNaN(val) || val === null || val === undefined) return "0,00";
        return val.toLocaleString('tr-TR', { minimumFractionDigits: 2, maximumFractionDigits: 2 });
    }

    function renderEditorItems() {
        const container = document.getElementById("itemsContainer");
        container.innerHTML = "";
        items.forEach((item, index) => {
            container.innerHTML += `
                <div style="border: 1px solid #e5e7eb; padding: 8px; margin-bottom: 8px; border-radius: 4px; background: #fafafa;">
                    <div style="display: flex; justify-content: space-between; margin-bottom: 4px;">
                        <strong style="font-size: 11px;">#${index + 1} Kalem</strong>
                        <button class="btn btn-danger" onclick="removeItem(${index})">Sil</button>
                    </div>
                    <div class="form-group">
                        <input type="text" placeholder="Ürün Açıklaması" value="${item.desc}" oninput="items[${index}].desc = this.value; renderPreview();">
                    </div>
                    <div class="form-row">
                        <div class="form-group" style="flex: 1;">
                            <input type="number" placeholder="Miktar" value="${item.qty}" oninput="items[${index}].qty = parseFloat(this.value)||0; renderPreview();">
                        </div>
                        <div class="form-group" style="flex: 1;">
                            <input type="text" placeholder="Birim (M2, ADET)" value="${item.unit}" oninput="items[${index}].unit = this.value; renderPreview();">
                        </div>
                        <div class="form-group" style="flex: 1;">
                            <input type="number" step="0.01" placeholder="Fiyat (KDV Dahil)" value="${item.price}" oninput="items[${index}].price = parseFloat(this.value)||0; renderPreview();">
                        </div>
                    </div>
                </div>
            `;
        });
    }

    function addItem() {
        items.push({ desc: "", qty: 1, unit: "ADET", price: 0 });
        renderEditorItems();
        renderPreview();
    }

    function removeItem(idx) {
        items.splice(idx, 1);
        renderEditorItems();
        renderPreview();
    }

    function updateForm() {
        document.getElementById("lblTarih").innerText = document.getElementById("inpTarih").value;
        document.getElementById("lblYetkili").innerText = document.getElementById("inpYetkili").value;
        document.getElementById("lblTelefon").innerText = document.getElementById("inpTelefon").value;
        document.getElementById("lblTeslimYeri").innerText = document.getElementById("inpTeslimYeri").value;
        document.getElementById("lblOdemeTarihi").innerText = document.getElementById("inpOdemeTarihi").value;
        document.getElementById("lblSatisSorumlusu").innerText = document.getElementById("inpSatisSorumlusu").value;
    }

    function renderPreview() {
        const tbody = document.getElementById("productRows");
        tbody.innerHTML = "";
        
        let totalMatrah = 0;
        let totalKdv = 0;
        let totalGenel = 0;

        const maxRows = 12;
        for (let i = 0; i < maxRows; i++) {
            if (i < items.length) {
                const item = items[i];
                const lineTotal = item.qty * item.price;
                const matrah = lineTotal / 1.20;
                const kdv = lineTotal - matrah;

                totalMatrah += matrah;
                totalKdv += kdv;
                totalGenel += lineTotal;

                tbody.innerHTML += `
                    <tr>
                        <td class="text-center">${i + 1}</td>
                        <td>${item.desc}</td>
                        <td class="text-center">${item.qty} ${item.unit}</td>
                        <td class="text-right">${fmt(item.price)}</td>
                        <td class="text-right">${fmt(kdv)}</td>
                        <td class="text-right">${fmt(lineTotal)}</td>
                    </tr>
                `;
            } else {
                tbody.innerHTML += `
                    <tr>
                        <td class="text-center">${i + 1}</td>
                        <td>&nbsp;</td>
                        <td></td>
                        <td></td>
                        <td></td>
                        <td></td>
                    </tr>
                `;
            }
        }

        document.getElementById("lblMatrah").innerText = fmt(totalMatrah);
        document.getElementById("lblKdvTutar").innerText = fmt(totalKdv);
        document.getElementById("lblGenelToplam").innerText = fmt(totalGenel);
    }

    function downloadPDF() {
        window.print();
    }

    function downloadExcel() {
        const dateStr = document.getElementById("inpTarih").value || "Tarih";
        const filename = `Teklif_Formu_${dateStr.replace(/\./g, '_')}.xls`;

        let excelHTML = `
        <html xmlns:o="urn:schemas-microsoft-com:office:office" xmlns:x="urn:schemas-microsoft-com:office:excel" xmlns="http://www.w3.org/TR/REC-html40">
        <head>
            <meta charset="utf-8">
            <!--[if gte mso 9]>
            <xml>
                <x:ExcelWorkbook>
                    <x:ExcelWorksheets>
                        <x:ExcelWorksheet>
                            <x:Name>Teklif Formu</x:Name>
                            <x:WorksheetOptions>
                                <x:DisplayGridlines/>
                            </x:WorksheetOptions>
                        </x:ExcelWorksheet>
                    </x:ExcelWorksheets>
                </x:ExcelWorkbook>
            </xml>
            <![endif]-->
            <style>
                table { border-collapse: collapse; font-family: Arial, sans-serif; font-size: 10pt; }
                td, th { border: 0.5pt solid #000000; padding: 4px; vertical-align: middle; }
                .bg-yellow { background-color: #FEF08A; font-weight: bold; }
                .bg-green { background-color: #BBF7D0; font-weight: bold; }
                .bg-red { background-color: #FF0000; color: #FFFFFF; font-weight: bold; text-align: center; }
                .bold { font-weight: bold; }
                .italic { font-style: italic; }
                .text-right { text-align: right; }
                .text-center { text-align: center; }
            </style>
        </head>
        <body>
            ${document.getElementById("invoicePaper").outerHTML}
        </body>
        </html>
        `;

        const blob = new Blob([excelHTML], { type: 'application/vnd.ms-excel;charset=utf-8' });
        const link = document.createElement("a");
        link.href = URL.createObjectURL(blob);
        link.download = filename;
        document.body.appendChild(link);
        link.click();
        document.body.removeChild(link);
    }

    // Uygulamayı Başlat
    renderEditorItems();
    renderPreview();
    updateForm();
</script>
</body>
</html>
