<form
  action="https://formspree.io/f/{FORM_ID}"
  class="fs-form fs-layout__2-column"
  target="_top"
  method="POST"
>
  <fieldset>
    <legend class="fs-fieldset-title">Requester Information</legend>
    <div class="fs-field">
      <label class="fs-label" for="requestor-name">Requestor Name</label>
      <input
        class="fs-input"
        id="requestor-name"
        name="requestor-name"
        placeholder="Enter your name"
        required
      />
    </div>
    <div class="fs-field">
      <label class="fs-label" for="department-team">Department / Team</label>
      <input
        class="fs-input"
        id="department-team"
        name="department-team"
        placeholder="Enter your department or team"
        required
      />
    </div>
    <div class="fs-field">
      <label class="fs-label" for="email-address">Email Address</label>
      <input
        class="fs-input"
        id="email-address"
        name="email-address"
        placeholder="Enter your email address"
        required
      />
    </div>
    <div class="fs-field">
      <label class="fs-label" for="phone-number">Phone Number</label>
      <input
        class="fs-input"
        id="phone-number"
        name="phone-number"
        placeholder="Enter your phone number (optional)"
      />
    </div>
    <div class="fs-field">
      <label class="fs-label" for="date-of-request">Date of Request</label>
      <input
        class="fs-input"
        id="date-of-request"
        name="date-of-request"
        placeholder="Enter the request date (YYYY-MM-DD)"
        required
      />
    </div>
  </fieldset>
  <fieldset>
    <legend class="fs-fieldset-title">Payment Details</legend>
    <div class="fs-field">
      <label class="fs-label" for="payment-amount">Payment Amount</label>
      <input
        class="fs-input"
        id="payment-amount"
        name="payment-amount"
        placeholder="Enter the payment amount"
        required
      />
    </div>
    <div class="fs-field">
      <label class="fs-label" for="currency">Currency</label>
      <select class="fs-select" id="currency" name="currency" required>
        <option value="usd">USD</option>
        <option value="eur">EUR</option>
        <option value="inr">INR</option>
      </select>
    </div>
    <div class="fs-field col-span-full">
      <label class="fs-label" for="payment-purpose">Purpose of Payment</label>
      <textarea
        class="fs-textarea"
        id="payment-purpose"
        name="payment-purpose"
        placeholder="Describe the purpose of this payment"
        required
      ></textarea>
    </div>
    <div class="fs-field">
      <label class="fs-label" for="invoice-reference">
        Invoice Number / Reference ID
      </label>
      <input
        class="fs-input"
        id="invoice-reference"
        name="invoice-reference"
        placeholder="Enter the invoice number or reference ID"
        required
      />
    </div>
    <div class="fs-field">
      <label class="fs-label" for="payee-name">Vendor or Payee Name</label>
      <input
        class="fs-input"
        id="payee-name"
        name="payee-name"
        placeholder="Enter the vendor or payee name"
        required
      />
    </div>
    <div class="fs-field col-span-full">
      <label class="fs-label" for="payee-contact">
        Vendor or Payee Contact Details
      </label>
      <textarea
        class="fs-textarea"
        id="payee-contact"
        name="payee-contact"
        placeholder="Enter payee contact details (optional)"
      ></textarea>
    </div>
    <div class="fs-field">
      <label class="fs-label" for="payment-method">
        Payment Method Requested
      </label>
      <select
        class="fs-select"
        id="payment-method"
        name="payment-method"
        required
      >
        <option value="bank-transfer">Bank Transfer</option>
        <option value="check">Check</option>
        <option value="paypal">PayPal</option>
        <option value="other">Other</option>
      </select>
    </div>
    <div class="fs-field">
      <label class="fs-label" for="due-date">Due Date for Payment</label>
      <input
        class="fs-input"
        id="due-date"
        name="due-date"
        placeholder="(YYYY-MM-DD)"
        required
      />
    </div>
    <div class="fs-field col-span-full">
      <label class="fs-label" for="payment-instrument-details">
        Payment Instrument Details (if applicable)
      </label>
      <textarea
        class="fs-textarea"
        id="payment-instrument-details"
        name="payment-instrument-details"
        placeholder="Enter the details of the chosen payment method if applicable (optional)"
      ></textarea>
    </div>
    <div class="fs-field col-span-full">
      <label class="fs-label" for="supporting-documents">
        Supporting Documents
      </label>
      <input
        class="fs-input"
        id="supporting-documents"
        name="supporting-documents"
        placeholder="Upload invoices, receipts, etc."
      />
    </div>
  </fieldset>
  <fieldset>
    <legend class="fs-fieldset-title">Approval and Confirmation</legend>
    <div class="fs-field">
      <label class="fs-label" for="approval-required-from">
        Approval Required From
      </label>
      <input
        class="fs-input"
        id="approval-required-from"
        name="approval-required-from"
        placeholder="Enter approver&#x27;s name or department"
        required
      />
    </div>
    <div class="fs-field">
      <label class="fs-label" for="additional-notes">
        Additional Notes or Special Instructions
      </label>
      <textarea
        class="fs-textarea"
        id="additional-notes"
        name="additional-notes"
        placeholder="Any extra notes or special handling instructions"
      ></textarea>
    </div>
    <div class="fs-checkbox-field col-span-full">
      <div class="fs-checkbox-wrapper">
        <input
          class="fs-checkbox"
          id="confirmation-opt-in"
          name="confirmation-opt-in"
          type="checkbox"
          value="yes"
        />
      </div>
      <div>
        <label class="fs-label" for="confirmation-opt-in">
          Would You Like Confirmation Once Paid?
        </label>
      </div>
    </div>
  </fieldset>
  <div class="fs-button-group">
    <button class="fs-button" type="submit">input</button>
  </div>
</form>
