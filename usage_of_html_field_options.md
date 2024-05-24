Sample Code:
------------------------------------------------------------------------------------
frappe.ui.form.on("DocType", {
	refresh(frm) {
      let msg = 
            `<div class="alert alert-info" role="alert">
                <p class="mb-0">
                    We are able to specify HTML content and enter those values into the HTML field that you specified.
                </p>
            </div>`

        cur_frm.fields_dict.message.wrapper.innerHTML = msg
        
	},
});
-------------------------------------------------------------------------------------
