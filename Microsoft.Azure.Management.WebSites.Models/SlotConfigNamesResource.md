<Type Name="SlotConfigNamesResource" FullName="Microsoft.Azure.Management.WebSites.Models.SlotConfigNamesResource">
  <TypeSignature Language="C#" Value="public class SlotConfigNamesResource : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SlotConfigNamesResource extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SlotConfigNamesResource" />
  <TypeSignature Language="VB.NET" Value="Public Class SlotConfigNamesResource&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SlotConfigNamesResource = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            スロットの構成は、azure リソースを名前です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SlotConfigNamesResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SlotConfigNamesResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SlotConfigNamesResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SlotConfigNamesResource (string id = null, string name = null, string kind = null, string type = null, System.Collections.Generic.IList&lt;string&gt; connectionStringNames = null, System.Collections.Generic.IList&lt;string&gt; appSettingNames = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, class System.Collections.Generic.IList`1&lt;string&gt; connectionStringNames, class System.Collections.Generic.IList`1&lt;string&gt; appSettingNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SlotConfigNamesResource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional connectionStringNames As IList(Of String) = null, Optional appSettingNames As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SlotConfigNamesResource : string * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.SlotConfigNamesResource" Usage="new Microsoft.Azure.Management.WebSites.Models.SlotConfigNamesResource (id, name, kind, type, connectionStringNames, appSettingNames)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="connectionStringNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="appSettingNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="connectionStringNames">接続文字列名の一覧です。</param>
        <param name="appSettingNames">アプリケーション設定の名前の一覧です。</param>
        <summary>
            SlotConfigNamesResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppSettingNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AppSettingNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AppSettingNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SlotConfigNamesResource.AppSettingNames" />
      <MemberSignature Language="VB.NET" Value="Public Property AppSettingNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AppSettingNames : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SlotConfigNamesResource.AppSettingNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appSettingNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のアプリケーション名の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionStringNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ConnectionStringNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ConnectionStringNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SlotConfigNamesResource.ConnectionStringNames" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionStringNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ConnectionStringNames : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SlotConfigNamesResource.ConnectionStringNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.connectionStringNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または接続文字列名の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>