<!DOCTYPE html>

<html lang="bn">
<head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>গুদাম স্টক ব্যবস্থাপনা  Anik Trader's LTD </title>
<style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #e0f7fa, #e0f2f1);
      color: #333;
    }
    header {
      background-color: #00695c;
      color: white;
      padding: 20px;
      text-align: center;
      font-size: 28px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
    marquee {
      background:#00796b;
      color:#e0f7fa;
      font-size:18px;
      padding:5px 0;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
      padding: 20px;
      gap: 20px;
    }
    .form-section {
      background: #ffffff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      flex: 1;
      max-width: 320px;
    }
    .form-section h3 {
      margin-top: 0;
      color: #00796b;
    }
    .form-section input, .form-section select {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    .form-section button {
      width: 100%;
      background: #00796b;
      color: white;
      border: none;
      padding: 10px;
      border-radius: 6px;
      cursor: pointer;
      font-size: 16px;
    }
    .form-section button:hover {
      background: #004d40;
    }
    .stock-section {
      flex: 2;
      background: #ffffff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    .stock-table, .history-table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }
    .stock-table th, .stock-table td,
    .history-table th, .history-table td {
      border: 1px solid #b2dfdb;
      padding: 10px;
      text-align: center;
    }
    .stock-table th {
      background-color: #004d40;
      color: white;
    }
    .history-table th {
      background-color: #00695c;
      color: white;
    }
    .totals {
      margin: 15px 0;
      font-weight: bold;
      font-size: 16px;
      color: #004d40;
    }
  
    .history-wrapper {
      max-height: 400px;
      overflow-y: auto;
      border: 1px solid #ccc;
      margin-top: 10px;
    }
</style>
</head>
<body>
<header>📦 গুদাম স্টক ব্যবস্থাপনা, অনিক ট্রেড্রার্স লিমিটেড  📦</header>
<marquee behavior="scroll" direction="right">Anik Trader's LTD, Adress: Chandrakona Bazar, Nakla, Sherpur Mobile: 01631110750 </marquee>
<div class="container">
<div class="form-section">
<h3>স্টক এন্ট্রি করুন</h3>
<select id="product" onchange="adjustInputs()" required="">
<option value="">-- পণ্য নির্বাচন করুন --</option>
<option value="চাল">চাল</option>
<option value="ধান">ধান</option>
<option value="গম">গম</option>
<option value="আটা">আটা</option>
<option value="কার্নেল">কার্নেল</option>
<option value="খালি বস্তা ৩০ কেজি">খালি বস্তা ৩০ কেজি</option>
<option value="খালি বস্তা ৫০ কেজি">খালি বস্তা ৫০ কেজি</option>
</select>
<input id="quantity" placeholder="পরিমাণ লিখুন (মে.টন হিসেবে)" required="" type="number"/>
<input id="bags" placeholder="বস্তা সংখ্যা লিখুন " required="" type="number"/>
<input id="value" placeholder="মোট মূল্য লিখুন (৳)" type="number"/>
<input id="entryDate" style="width:100%; margin-bottom:10px; padding:10px;" type="date"/><input id="remark" placeholder="রিমার্কস  (ক্রেতা/বিক্রেতার তথ্য)" required="" type="text"/>
<select id="action" required="">
<option value="add"> পণ্য স্টকে যোগ করুন</option>
<option value="remove">পণ্য স্টক থেকে বাদ দিন</option>
</select>
<button onclick="addStock()">✅ পণ্য এন্ট্রি দিন</button>
<button onclick="resetData()" style="margin-top:10px; background:red;">🗑️ রিসেট করুন সকল ডাটা </button>
</div>
<div class="stock-section">
<div style="margin-bottom:10px;">🔍 তারিখ দিয়ে ফিল্টার করুন হিস্টোরি :<input id="filterDate" onchange="filterByDate()" type="date"/></div><h3>বর্তমান স্টক </h3>
<div id="totals"></div>
<table class="stock-table" id="stockTable">
<thead>
<tr>
<th>পণ্য</th>
<th>পরিমাণ</th>
<th>বস্তা</th>
<th>মূল্য (৳)</th>
</tr>
</thead>
<tbody></tbody>
</table>
<h3 style="margin-top:30px; display: flex; justify-content: space-between; align-items: center;">
<span>লেনদেন হিস্ট্রি দেখুন</span>
<span>
<button onclick="exportToExcel()" style="background:none; border:none; cursor:pointer;" title="এক্সেল ডাউনলোড করুন">
<img alt="Excel" src="https://img.icons8.com/color/24/microsoft-excel-2019.png"/>
</button>
<button onclick="exportToPDF()" style="background:none; border:none; cursor:pointer;" title="PDF ডাউনলোড করুন">
<img alt="PDF" src="https://img.icons8.com/color/24/pdf.png"/>
</button>
</span>
</h3>
<div class="history-wrapper"><table class="history-table" id="historyTable">
<thead>
<tr><th>ক্রম. নং</th>
<th>তারিখ</th>
<th>পণ্য</th>
<th>পরিমাণ</th>
<th>বস্তা</th>
<th>মূল্য</th>
<th>ধরন</th>
<th>রিমার্কস/ডকুমেন্ট</th>
<th>ইডিট করুন</th>
</tr>
</thead>
<tbody></tbody>
</table></div>
</div>
</div>
<div id="editModal" style="display:none; position:fixed; top:0; left:0; width:100%; height:100%; background:rgba(0,0,0,0.6); z-index:1000; justify-content:center; align-items:center;">
<div style="background:white; padding:20px; border-radius:10px; width:300px;">
<h3>🔐 এন্ট্রি সংশোধন করুন, অবশ্যয় কর্তৃপক্ষের অনুমতি সাপেক্ষে </h3>
<input id="editPassword" placeholder=" সঠিক পাসওয়ার্ড দিন" style="width:100%; margin-bottom:10px; padding:8px;" type="password"/>
<input id="editQuantity" placeholder="পরিমাণ" style="width:100%; margin-bottom:10px; padding:8px;" type="number"/>
<input id="editBags" placeholder="বস্তা" style="width:100%; margin-bottom:10px; padding:8px;" type="number"/>
<input id="editValue" placeholder="মূল্য" style="width:100%; margin-bottom:10px; padding:8px;" type="number"/>
<input id="editRemark" placeholder="রিমার্কস" style="width:100%; margin-bottom:10px; padding:8px;" type="text"/>
<button onclick="confirmEdit()" style="background:#00796b; color:white; padding:10px; width:100%; border:none; border-radius:6px;">✅ সেভ করুন নতুন ডাটা</button>
<button onclick="closeModal()" style="margin-top:10px; background:#aaa; color:white; padding:10px; width:100%; border:none; border-radius:6px;">❌ বাতিল করুন</button>
</div>
</div>
<script>
const stock = JSON.parse(localStorage.getItem('stock') || '{}');
const history = JSON.parse(localStorage.getItem('history') || '[]');
const pricePerTon = {
  'ধান': 36000,
  'চাল': 53000,
  'গম': 51000,
  'আটা': 35000,
  'খালি বস্তা ৩০ কেজি': 50,
  'খালি বস্তা ৫০ কেজি': 50,
  'কার্ণেল': 20000,
};
const bagRatio = 25;
let currentEditIndex = null;

function adjustInputs() {
  const product = document.getElementById('product').value;
  const qtyInput = document.getElementById('quantity');
  const valInput = document.getElementById('value');
  const bagsInput = document.getElementById('bags');
  qtyInput.addEventListener('input', () => {
    const qty = parseFloat(qtyInput.value) || 0;
    if (product.includes('খালি বস্তা') || product === 'কার্নেল') {
      valInput.value = qty * 50;
      bagsInput.value = qty;
    } else {
      valInput.value = (pricePerTon[product] || 0) * qty;
      bagsInput.value = qty * bagRatio;
    }
  });
}

function addStock() {
  const product = document.getElementById('product').value;
  const quantity = parseFloat(document.getElementById('quantity').value);
  const bags = parseInt(document.getElementById('bags').value);
  const value = parseFloat(document.getElementById('value').value);
  const remark = document.getElementById('remark').value.trim();
  const action = document.getElementById('action').value;
  const date = document.getElementById('entryDate').value || new Date().toISOString().slice(0, 10);
  if (!product || !quantity || !bags || !value || !remark || !action) {
    alert('সব ঘর পূরণ করা বাধ্যতামূলক!');
    return;
  }
  if (!stock[product]) {
    stock[product] = { quantity: 0, bags: 0, value: 0 };
  }
  if (action === 'add') {
    stock[product].quantity += quantity;
    stock[product].bags += bags;
    stock[product].value += value;
  } else {
    stock[product].quantity -= quantity;
    stock[product].bags -= bags;
    stock[product].value -= value;
  }
  history.push({
    date: date,
    product,
    quantity,
    bags,
    value,
    type: action === 'add' ? 'গুদামে ঢুকেছে ' : 'গুদাম থেকে বের হয়েছে',
    remark
  });
  localStorage.setItem('stock', JSON.stringify(stock));
  localStorage.setItem('history', JSON.stringify(history));
  render();
  document.querySelectorAll('.form-section input').forEach(i => i.value = '');
  document.getElementById('product').value = '';
  document.getElementById('action').value = 'add';
}

function render(filterDate = "") {
  const table = document.querySelector('#stockTable tbody');
  const historyTable = document.querySelector('#historyTable tbody');
  const totals = document.getElementById('totals');
  table.innerHTML = '';
  historyTable.innerHTML = '';
  let totalMT = 0, totalBags = 0, totalValue = 0;
  for (let p in stock) {
    const s = stock[p];
    table.innerHTML += `<tr><td>${p}</td><td>${s.quantity.toFixed(3)}</td><td>${s.bags}</td><td>${Math.round(s.value)}</td></tr>`;
    totalMT += s.quantity;
    totalBags += s.bags;
    totalValue += s.value;
  }
  totals.innerText = `মোট  বর্তমান মজুদ দেখুন ➤ ${totalMT.toFixed(3)} মে.টন/পিস হিসেবে | ${totalBags} বস্তা | ৳${Math.round(totalValue)}`;
  
let serial = 1;
[...history].reverse().forEach((h, i) => {
  if (filterDate && h.date !== filterDate) return;
  historyTable.innerHTML += `<tr><td>${serial++}</td><td>${h.date}</td><td>${h.product}</td><td>${h.quantity}</td><td>${h.bags}</td><td>${h.value}</td><td>${h.type}</td><td>${h.remark}</td><td><button onclick='editEntry(${history.length - 1 - i})'>✏️</button></td></tr>`;
});
}

function resetData() {
  const password = prompt("রিসেট করতে পাসওয়ার্ড দিন:");
  if (password === "Anik7820**") {
    if (confirm("আপনি কি নিশ্চিত রিসেট করতে চান? সব তথ্য মুছে যাবে!")) {
      localStorage.removeItem('stock');
      localStorage.removeItem('history');
      alert("সফলভাবে রিসেট হয়েছে!");
      location.reload();
    }
  } else {
    alert("ভুল পাসওয়ার্ড সাবধান!");
  }
}

function editEntry(index) {
  currentEditIndex = index;
  const h = history[index];
  document.getElementById("editPassword").value = "";
  document.getElementById("editQuantity").value = h.quantity;
  document.getElementById("editBags").value = h.bags;
  document.getElementById("editValue").value = h.value;
  document.getElementById("editRemark").value = h.remark;
  document.getElementById("editModal").style.display = "flex";
}

function closeModal() {
  document.getElementById("editModal").style.display = "none";
}

function confirmEdit() {
  const pass = document.getElementById("editPassword").value;
  if (pass !== "anik7820") {
    alert("❌ ভুল পাসওয়ার্ড দিয়েছে দয়া করে সঠিক পাসওয়ার্ড দিন!");
    return;
  }
  const quantity = parseFloat(document.getElementById("editQuantity").value);
  const bags = parseInt(document.getElementById("editBags").value);
  const value = parseFloat(document.getElementById("editValue").value);
  const remark = document.getElementById("editRemark").value.trim();
  if (!quantity || !bags || !value || !remark) {
    alert("⚠️ সব ঘর পূরণ বাধ্যতামূলক");
    return;
  }
  const h = history[currentEditIndex];
  const product = h.product;
  if (h.type === 'যোগ') {
    stock[product].quantity -= h.quantity;
    stock[product].bags -= h.bags;
    stock[product].value -= h.value;
  } else {
    stock[product].quantity += h.quantity;
    stock[product].bags += h.bags;
    stock[product].value += h.value;
  }
  h.quantity = quantity;
  h.bags = bags;
  h.value = value;
  h.remark = remark;
  if (h.type === 'যোগ') {
    stock[product].quantity += quantity;
    stock[product].bags += bags;
    stock[product].value += value;
  } else {
    stock[product].quantity -= quantity;
    stock[product].bags -= bags;
    stock[product].value -= value;
  }
  localStorage.setItem('history', JSON.stringify(history));
  localStorage.setItem('stock', JSON.stringify(stock));
  closeModal();
  render();
}

function filterByDate() {
  const date = document.getElementById('filterDate').value;
  render(date);
}

render();
    </script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.17.0/xlsx.full.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf-autotable/3.5.25/jspdf.plugin.autotable.min.js"></script>
<script>
function exportToExcel() {
    const table = document.getElementById("historyTable");
    const wb = XLSX.utils.table_to_book(table, {sheet: "History"});
    XLSX.writeFile(wb, "লেনদেন_হিস্টোরি.xlsx");
}
async function exportToPDF() {
    const { jsPDF } = window.jspdf;
    const doc = new jsPDF();
    doc.text("লেনদেন হিস্টোরি", 14, 16);
    const table = document.getElementById("historyTable");
    let rows = [];
    for (let r of table.rows) {
        let row = [];
        for (let c of r.cells) row.push(c.innerText);
        rows.push(row);
    }
    doc.autoTable({
        head: [rows[0]],
        body: rows.slice(1),
        startY: 20,
    });
    doc.save("লেনদেন_হিস্টোরি.pdf");
}
</script>
</body>
</html>
