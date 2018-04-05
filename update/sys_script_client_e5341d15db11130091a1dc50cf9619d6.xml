<?xml version="1.0" encoding="UTF-8"?>
<record_update sys_domain="global" table="sys_script_client">
    <sys_script_client action="INSERT_OR_UPDATE">
        <active>true</active>
        <applies_extended>false</applies_extended>
        <condition/>
        <description/>
        <field/>
        <global>true</global>
        <messages/>
        <name/>
        <order/>
        <script><![CDATA[function onChange(control, oldValue, newValue, isLoading) {
	if (isLoading || newValue == '') {
		return;
	}
	
	//Type appropriate comment here, and begin script below
	
	if ((newValue == "New Account Request") || (newValue == "Update to an existing account")) {
		
		g_form.setVisible('api_module', true);
		
		g_form.setVisible('api_asset', true);
		g_form.setValue('api_asset',false);
		g_form.setValue('api_asset_rest_action_read',false);
		g_form.setValue('api_asset_rest_action_write',false);
		
		g_form.setVisible('api_change', true);
		g_form.setValue('api_change',false);
		g_form.setValue('api_change_rest_action_read',false);
		g_form.setValue('api_change_rest_action_write',false);
		
		g_form.setVisible('api_problem', true);
		g_form.setValue('api_problem',false);
		g_form.setValue('api_problem_rest_action_read',false);
		
		g_form.setVisible('api_config', true);
		g_form.setValue('api_config',false);
		g_form.setValue('api_config_rest_action_read',false);
		g_form.setValue('api_config_rest_action_write',false);
		
		g_form.setVisible('api_request', true);
		g_form.setValue('api_request',false);
		g_form.setValue('api_request_rest_action_read',false);
		g_form.setValue('api_request_rest_action_write',false);
		
		g_form.setVisible('api_core', true);
		g_form.setValue('api_core',false);
		g_form.setValue('api_core_rest_action_read',false);
		
		g_form.setVisible('api_incident', true);
		g_form.setValue('api_incident',false);
		g_form.setValue('api_inc_rest_action_read',false);
		g_form.setValue('api_inc_rest_action_write',false);
		
		// Rest Action variables:
		g_form.setValue('api_change_type_normal', false);
		g_form.setValue('api_change_type_standard', false);
		g_form.setValue('api_change_type_emergency', false);
		g_form.setValue('api_change_ticket_source', '');
		g_form.setValue('api_change_ticket_comp', '');
		g_form.setValue('api_change_frontend', '');
		g_form.setValue('api_config_req', '');
		g_form.setValue('api_config_ci', '');
		g_form.setValue('api_config_usecase', '');
		g_form.setValue('api_config_data', '');
		g_form.setValue('api_config_req_timeline', '');
		g_form.setValue('api_config_link', '');
		g_form.setValue('api_inc_action_create', false);
		g_form.setValue('api_inc_action_update', false);
		g_form.setValue('api_inc_action_read', false);
		g_form.setValue('api_inc_openedby', '');
		g_form.setValue('api_inc_ticket_source', '');
		g_form.setValue('api_inc_ticket_comp', '');
		g_form.setValue('api_inc_frontend', '');
		g_form.setValue('api_inc_monitoring', '');
		g_form.setValue('api_inc_frontend_yes', '');
		g_form.setValue('api_inc_monitoring_yes', '');
		g_form.setValue('api_request_items', '');
		g_form.setValue('api_request_ticket_source', '');
		g_form.setValue('api_request_ticket_comp', '');
		g_form.setValue('api_request_frontend', '');
		g_form.setValue('api_request_req', '');
		g_form.setValue('api_request_items_yes', '');
		g_form.setValue('api_asset_req', '');
		g_form.setValue('api_asset_action', '');
		g_form.setValue('api_asset_usecase', '');
		g_form.setValue('api_asset_data', '');
		g_form.setValue('api_asset_link', '');
		
	}else{
		g_form.setVisible('api_module', false);
		g_form.setVisible('api_asset', false);
		g_form.setVisible('api_change', false);
		g_form.setVisible('api_problem', false);
		g_form.setVisible('api_config', false);
		g_form.setVisible('api_request', false);
		g_form.setVisible('api_core', false);
		g_form.setVisible('api_incident', false);
	}
	
}]]></script>
        <sys_class_name>sys_script_client</sys_class_name>
        <sys_created_by>admin</sys_created_by>
        <sys_created_on>2018-04-05 05:24:24</sys_created_on>
        <sys_domain>global</sys_domain>
        <sys_domain_path>/</sys_domain_path>
        <sys_id>e5341d15db11130091a1dc50cf9619d6</sys_id>
        <sys_mod_count>0</sys_mod_count>
        <sys_name/>
        <sys_overrides/>
        <sys_package display_value="final" source="x_192889_final">1ac31d11db11130091a1dc50cf961944</sys_package>
        <sys_policy/>
        <sys_scope display_value="final">1ac31d11db11130091a1dc50cf961944</sys_scope>
        <sys_update_name>sys_script_client_e5341d15db11130091a1dc50cf9619d6</sys_update_name>
        <sys_updated_by>admin</sys_updated_by>
        <sys_updated_on>2018-04-05 05:24:24</sys_updated_on>
        <table/>
        <type/>
        <ui_type>0</ui_type>
        <view/>
    </sys_script_client>
</record_update>
