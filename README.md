# park-world-lightning-framework

<code>sfdx plugins --core</code>

<code>SFDX: Create file with manifest</code>
  
<code>sfdx force:auth:web:login -s</code>
    
<code>sfdx force:source:deploy -x manifest/package.xml</code>

<code>sfdx force:source:retrieve -x manifest/package.xml</code>

<code>npm init</code>

<code>"devDependencies": {
    "@salesforce-ux/design-system":"2.7.5"
  }
</code>

<code>sfdx force:source:delete -p force-app/main/default/aura</code>

  

<code>
var items = [
      {name: 1, label: 'Henry Wu', expanded: true, items: []},
  {name: 2, label: 'Ellie Sattler', expanded: true, items: []},
  {name: 3, label: 'Ian Malcolm', expanded: true, items: []},
  {name: 4, label: 'John Hammond', expanded: true, items: []},
  {name: 5, label: 'Sarah Harding', expanded: true, items: []},
  {name: 6, label: 'Alan Grant', expanded: true, items: []},
  {name: 7, label: 'Dennis Nedry', expanded: true, items: []},
  {name: 8, label: 'Dr. Harding', expanded: true, items: []},
  {name: 9, label: 'Ray Arnold', expanded: true, items: []}
    ];
 </code>
 
    <aura:component implements="flexipage:availableForAllPageTypes">
      <aura:handler name="init" value="{!this}" action="{!c.init}" />
        <aura:attribute name="items" type="Object" access="PRIVATE"/>
        <lightning:tree items="{! v.items }" header="Scientists"/>
    </aura:component>
