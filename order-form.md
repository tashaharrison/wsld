---
layout: page
title: Order Form
permalink: /order-form/
---
<b>Deadline for September 2016 orders: Wednesday 17th August </b><br><em>All orders placed before this time will arrive on Thursday 1st September 2016.</em>

Before you place your order, please check the <a class="button" href="/booklet-contents">booklet contents</a> and <a class="button" href="/price-guide">price guide</a>.<br>After you place your order, you will receive a quote within 24 hours; you will still be able to make changes to or cancel your order.

<form action="https://getsimpleform.com/messages?form_api_token=d3d371453b8aeb87b4aec39b0650ef1c" method="post">
  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <input type='hidden' name='redirect_to' value='http://whosaidlatinsdead.com/thank-you/' />

  <!-- input fields -->
  <fieldset>
    <legend>Workbooks & PDFs</legend>
    <table class="workbooks">
      <thead>
        <tr>
          <td></td>
          <td>Number of <br />copies</td>
          <td>Additional PDF<br /> (please tick)</td>
          <td>PDF with printing licence<br /> (please tick)</td>
        </tr>
      </thead>
      <tbody>
        <tr class="header first"><td>Level 1</td></tr>
        <tr>
          <td><label>Level 1 Book 1</label></td>
          <td><input type='text' name='l1_b1_no_copies'></td>
          <td><input type="checkbox" name="l1_b1_additional_pdf" value="yes"></td>
          <td><input type="checkbox" name="l1_b1_printing_pdf" value="yes" ></td>
        </tr>
        <tr>
          <td><label>Level 1 Book 2</label></td>
          <td><input type='text' name='l1_b2_no_copies'></td>
          <td><input type="checkbox" name="l1_b2_additional_pdf" value="yes"></td>
          <td><input type="checkbox" name="l1_b2_printing_pdf" value="yes" ></td>
        </tr>
        <tr>
          <td><label>Level 1 Book 3</label></td>
          <td><input type='text' name='l1_b3_no_copies'></td>
          <td><input type="checkbox" name="l1_b3_additional_pdf" value="yes"></td>
          <td><input type="checkbox" name="l1_b3_printing_pdf" value="yes" ></td>
        </tr>
        <tr>
          <td><label>Level 1 Book 4</label></td>
          <td><input type='text' name='l1_b4_no_copies'></td>
          <td><input type="checkbox" name="l1_b4_additional_pdf" value="yes"></td>
          <td><input type="checkbox" name="l1_b4_printing_pdf" value="yes" ></td>
        </tr>
        <tr class="header"><td>Level 2</td></tr>
        <tr>
          <td><label>Level 2 Book 1</label></td>
          <td><input type='text' name='l2_b1_no_copies'></td>
          <td><input type="checkbox" name="l2_b1_additional_pdf" value="yes"></td>
          <td><input type="checkbox" name="l2_b1_printing_pdf" value="yes" ></td>
        </tr>
        <tr>
          <td><label>Level 2 Book 2</label></td>
          <td><input type='text' name='l2_b2_no_copies'></td>
          <td><input type="checkbox" name="l2_b2_additional_pdf" value="yes"></td>
          <td><input type="checkbox" name="l2_b2_printing_pdf" value="yes" ></td>
        </tr>
        <tr>
          <td><label>Level 2 Book 3</label></td>
          <td><input type='text' name='l2_b3_no_copies'></td>
          <td><input type="checkbox" name="l2_b3_additional_pdf" value="yes"></td>
          <td><input type="checkbox" name="l2_b3_printing_pdf" value="yes" ></td>
        </tr>
        <tr>
          <td><label>Level 2 Book 4</label></td>
          <td><input type='text' name='l2_b4_no_copies'></td>
          <td><input type="checkbox" name="l2_b4_additional_pdf" value="yes"></td>
          <td><input type="checkbox" name="l2_b4_printing_pdf" value="yes" ></td>
        </tr>
        <tr class="header"><td>Level 3</td></tr>
        <tr>
          <td><label>Level 3 Book 1</label></td>
          <td><input type='text' name='l3_b1_no_copies'></td>
          <td><input type="checkbox" name="l3_b1_additional_pdf" value="yes"></td>
          <td><input type="checkbox" name="l3_b1_printing_pdf" value="yes" ></td>
        </tr>
        <tr>
          <td><label>Level 3 Book 2</label></td>
          <td><input type='text' name='l3_b2_no_copies'></td>
          <td><input type="checkbox" name="l3_b2_additional_pdf" value="yes"></td>
          <td><input type="checkbox" name="l3_b2_printing_pdf" value="yes" ></td>
        </tr>
        <tr>
          <td><label>Level 3 Book 3</label></td>
          <td><input type='text' name='l3_b3_no_copies'></td>
          <td><input type="checkbox" name="l3_b3_additional_pdf" value="yes"></td>
          <td><input type="checkbox" name="l3_b3_printing_pdf" value="yes" ></td>
        </tr>
        <tr>
          <td><label>Level 3 Book 4</label></td>
          <td><input type='text' name='l3_b4_no_copies'></td>
          <td><input type="checkbox" name="l3_b4_additional_pdf" value="yes"></td>
          <td><input type="checkbox" name="l3_b4_printing_pdf" value="yes" ></td>
        </tr>
      </tbody>
    </table>
  </fieldset>

  <fieldset>
    <legend>Contact & Delivery</legend>
    <table>
      <tr>
        <td class="left"><label>Contact Name</label></td><td><input type="text" name="contact_name"></td>
      </tr>
      <tr>
        <td class="left"><label>Email Address</label></td><td><input type="text" name="email"></td>
      </tr>
      <tr>
        <td class="left"><label>School</label></td><td><input type="text" name="school"></td>
      </tr>
      <tr>
        <td class="left"><label>Delivery Address</label></td><td><textarea name="address"></textarea></td>
      </tr>
    </table>
  </fieldset>

  <input type='submit' value='Submit Order' />
</form>
