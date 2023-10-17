# WPF
Web Payment Form
<?xml version="1.0" encoding="UTF-8"?>
  <wpf_payment>
    <transaction_id>Vitor-WPF-{{$timestamp}}</transaction_id>
    <usage>40208 concert tickets</usage>
    <description>You are about to buy 3 shoes at www.shoes.com!</description>
    <notification_url>https://www.example.com/notification</notification_url>
    <return_success_url>https://www.emerchantpay.com/</return_success_url>
    <return_failure_url>http://www.google.com</return_failure_url>
    <return_cancel_url>http://www.example.com/cancel.html</return_cancel_url>
    <return_pending_url>http://www.example.com/payment-pending.html</return_pending_url>
    <amount>100</amount>
    <currency>EUR</currency>
    <consumer_id></consumer_id>
    <customer_email>vitor.monteiro@emerchantpay.com</customer_email>
    <customer_phone>+1987987987987</customer_phone>
    <remember_card>true</remember_card>
    <lifetime>60</lifetime>
    <billing_address>
      <first_name>Vitor</first_name>
      <last_name>Monteiro</last_name>
      <address1>Amsterdam</address1>
      <zip_code>1016</zip_code>
      <city>Amsterdam</city>
      <country>NL</country>
    </billing_address>
    <risk_params>
      <user_id>123456</user_id>
    </risk_params>
    <transaction_types>
      <transaction_type name="authorize"/>
      <transaction_type name="sale"/>
    </transaction_types>
    <business_attributes>
      <name_of_the_supplier>Best Furniture</name_of_the_supplier>
    </business_attributes>
    <sca_params>
      <exemption>low_value</exemption>
    </sca_params>
  </wpf_payment>
