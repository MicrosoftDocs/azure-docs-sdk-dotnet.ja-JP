<Type Name="HostName" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.HostName">
  <TypeSignature Language="C#" Value="public class HostName" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HostName extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.HostName" />
  <TypeSignature Language="VB.NET" Value="Public Class HostName" />
  <TypeSignature Language="F#" Value="type HostName = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ホスト名の詳細については、ドメインから派生します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HostName ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.HostName.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ホスト名クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HostName (string name = null, System.Collections.Generic.IList&lt;string&gt; siteNames = null, string azureResourceName = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType&gt; azureResourceType = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType&gt; customHostNameDnsRecordType = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType&gt; hostNameType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; siteNames, string azureResourceName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType&gt; azureResourceType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType&gt; customHostNameDnsRecordType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType&gt; hostNameType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.HostName.#ctor(System.String,System.Collections.Generic.IList{System.String},System.String,System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional siteNames As IList(Of String) = null, Optional azureResourceName As String = null, Optional azureResourceType As Nullable(Of AzureResourceType) = null, Optional customHostNameDnsRecordType As Nullable(Of CustomHostNameDnsRecordType) = null, Optional hostNameType As Nullable(Of HostNameType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.HostName : string * System.Collections.Generic.IList&lt;string&gt; * string * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.HostName" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.HostName (name, siteNames, azureResourceName, azureResourceType, customHostNameDnsRecordType, hostNameType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="siteNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="azureResourceName" Type="System.String" />
        <Parameter Name="azureResourceType" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType&gt;" />
        <Parameter Name="customHostNameDnsRecordType" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType&gt;" />
        <Parameter Name="hostNameType" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType&gt;" />
      </Parameters>
      <Docs>
        <param name="name">ホスト名の名前です。</param>
        <param name="siteNames">ホスト名が割り当てられているアプリの一覧。
            この一覧は、ホスト名が Traffic Manager を指している場合にのみ、1 つ以上のアプリがあります。</param>
        <param name="azureResourceName">ホスト名が割り当てられている Azure リソースの名前。 割り当てられている場合、Traffic Manager を Traffic Manager の名前が行われますそうでなければ、アプリ名です。</param>
        <param name="azureResourceType">ホスト名が割り当てられている Azure リソースの種類。 使用可能な値が含まれます: 'Website'、'TrafficManager'</param>
        <param name="customHostNameDnsRecordType">DNS レコードの型。
            使用可能な値が含まれます: 'CName'、'A'</param>
        <param name="hostNameType">ホスト名の型。 使用可能な値が含まれます: '検証済み'、'管理'</param>
        <summary>
            ホスト名クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureResourceName">
      <MemberSignature Language="C#" Value="public string AzureResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzureResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostName.AzureResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureResourceName As String" />
      <MemberSignature Language="F#" Value="member this.AzureResourceName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostName.AzureResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureResourceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定に、ホスト名が割り当てられている Azure リソースの名前。 割り当てられている場合、Traffic Manager を Traffic Manager の名前が行われますそうでなければ、アプリ名です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureResourceType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType&gt; AzureResourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType&gt; AzureResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostName.AzureResourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureResourceType As Nullable(Of AzureResourceType)" />
      <MemberSignature Language="F#" Value="member this.AzureResourceType : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostName.AzureResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureResourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AzureResourceType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはにホスト名が割り当てられている Azure リソースの種類を設定します。 使用可能な値が含まれます: 'Website'、'TrafficManager'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomHostNameDnsRecordType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType&gt; CustomHostNameDnsRecordType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType&gt; CustomHostNameDnsRecordType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostName.CustomHostNameDnsRecordType" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomHostNameDnsRecordType As Nullable(Of CustomHostNameDnsRecordType)" />
      <MemberSignature Language="F#" Value="member this.CustomHostNameDnsRecordType : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostName.CustomHostNameDnsRecordType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="customHostNameDnsRecordType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または DNS レコードの種類を設定します。 使用可能な値が含まれます: 'CName'、'A'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType&gt; HostNameType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType&gt; HostNameType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostName.HostNameType" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameType As Nullable(Of HostNameType)" />
      <MemberSignature Language="F#" Value="member this.HostNameType : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostName.HostNameType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hostNameType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはホスト名の型を設定します。 使用可能な値が含まれます: '検証済み'、'管理'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostName.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostName.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはホスト名の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SiteNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SiteNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostName.SiteNames" />
      <MemberSignature Language="VB.NET" Value="Public Property SiteNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SiteNames : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostName.SiteNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="siteNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはにホスト名が割り当てられているアプリの一覧を設定します。 この一覧は、ホスト名が Traffic Manager を指している場合にのみ、1 つ以上のアプリがあります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>