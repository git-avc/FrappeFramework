# JavaScript

### 1. Dynamically Fetching Select Options
```
frappe.ui.form.on("DocType Name", {
    refresh: function(frm) {
      var dynamic_options = ["Option 1", "Option 2"];
      frm.set_df_property("select_filed_name", "options", dynamic_options);
    }
  });
```
