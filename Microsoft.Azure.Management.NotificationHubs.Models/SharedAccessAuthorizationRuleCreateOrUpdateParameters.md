<Type Name="SharedAccessAuthorizationRuleCreateOrUpdateParameters" FullName="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters">
  <TypeSignature Language="C#" Value="public class SharedAccessAuthorizationRuleCreateOrUpdateParameters : Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedAccessAuthorizationRuleCreateOrUpdateParameters extends Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedAccessAuthorizationRuleCreateOrUpdateParameters&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type SharedAccessAuthorizationRuleCreateOrUpdateParameters = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.NotificationHubs.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            CreateOrUpdate Namespace AuthorizationRules に渡されるパラメーター。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAuthorizationRuleCreateOrUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SharedAccessAuthorizationRuleCreateOrUpdateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAuthorizationRuleCreateOrUpdateParameters (string location, Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties properties, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.NotificationHubs.Models.Sku sku = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties properties, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.NotificationHubs.Models.Sku sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters.#ctor(System.String,Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.NotificationHubs.Models.Sku)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters : string * Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.NotificationHubs.Models.Sku -&gt; Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters (location, properties, id, name, type, tags, sku)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.NotificationHubs.Models.Sku" />
      </Parameters>
      <Docs>
        <param name="location">リソースの場所</param>
        <param name="properties">Namespace AuthorizationRules のプロパティです。</param>
        <param name="id">リソース Id</param>
        <param name="name">リソース名</param>
        <param name="type">リソースの種類</param>
        <param name="tags">リソース タグ</param>
        <param name="sku">作成された名前空間の sku</param>
        <summary>
            SharedAccessAuthorizationRuleCreateOrUpdateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As SharedAccessAuthorizationRuleProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Namespace AuthorizationRules のプロパティを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>