# srshopbd.form
index.html
<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>SR Shop BD - Order Confirm Form</title>
<style>
  body { font-family: Arial, sans-serif; background:#f5f5f5; padding:20px; }
  .container { max-width:600px; margin:auto; background:#fff; padding:20px; border-radius:10px; box-shadow:0 0 10px rgba(0,0,0,0.1); }
  h2 { text-align:center; }
  label { font-weight:bold; margin-top:10px; display:block; }
  input, select, textarea { width:100%; padding:10px; margin-top:5px; border:1px solid #ccc; border-radius:5px; }
  button { width:100%; padding:12px; background:#28a745; color:#fff; border:none; border-radius:5px; margin-top:20px; cursor:pointer; font-size:16px; }
  button:hover { background:#218838; }
</style>
</head>
<body>
  <div class="container">
    <div style="text-align:center; margin-bottom:20px;">
      <img src="https://drive.google.com/uc?export=view&id=1t866gD4AeblC2Cl0s-cRCHrBfU74W-23" alt="SR Shop BD Logo" style="width:180px; margin-bottom:10px;" />
    </div>
    <h2>SR Shop BD - অর্ডার কনফার্ম ফর্ম</h2>

    <form>
      <label>১. নাম</label>
      <input type="text" required />

      <label>২. মোবাইল নাম্বার</label>
      <input type="text" required />

      <label>৩. বিভাগ সিলেক্ট করুন</label>
      <select required>
        <option value="">সিলেক্ট করুন</option>
        <option>ঢাকা</option>
        <option>চট্টগ্রাম</option>
        <option>রাজশাহী</option>
        <option>খুলনা</option>
        <option>বরিশাল</option>
        <option>সিলেট</option>
        <option>রংপুর</option>
        <option>ময়মনসিংহ</option>
      </select>

      <label>৪. আপনার জেলা সিলেক্ট করুন</label>
      <input type="text" required />

      <label>৫. আপনার থানা সিলেক্ট করুন</label>
      <input type="text" required />

      <label>৬. আপনার সম্পূর্ণ ঠিকানা লিখে দেন</label>
      <textarea rows="3" required></textarea>

      <label>৭. সাইজ (যদি থাকে)</label>
      <input type="text" />

      <label>৮. কালার ও ছবি স্ক্রিনশট আপলোড করুন</label>
      <input type="file" accept="image/*" />

      <p><strong>ডেলিভারি চার্জ:</strong><br>ঢাকার মধ্যে ৭০ টাকা<br>সাব-ঢাকা ১০০ টাকা<br>ঢাকার বাহিরে ১৩০ টাকা</p>

      <p><strong>পেমেন্ট করুন:</strong><br>
      বিকাশ / নগদ / উপায় / রকেট<br>
      01516392628 (Send Money)</p>

      <p><strong>ব্যাংক ট্রান্সফার:</strong><br>
      NexusPay / Visa<br>
      4840 6100 1303 7033<br>
      Miss Samina Akther</p>

      <p><strong>ডেলিভারি সময়:</strong> ২–৫ দিনের মধ্যে</p>

      <button type="submit">অর্ডার কনফার্ম করুন</button>
    </form>
  </div>
</body>
</html>
