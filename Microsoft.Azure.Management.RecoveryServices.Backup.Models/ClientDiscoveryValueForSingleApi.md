<Type Name="ClientDiscoveryValueForSingleApi" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryValueForSingleApi">
  <TypeSignature Language="C#" Value="public class ClientDiscoveryValueForSingleApi" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClientDiscoveryValueForSingleApi extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryValueForSingleApi" />
  <TypeSignature Language="VB.NET" Value="Public Class ClientDiscoveryValueForSingleApi" />
  <TypeSignature Language="F#" Value="type ClientDiscoveryValueForSingleApi = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            使用可能な操作の詳細。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientDiscoveryValueForSingleApi ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryValueForSingleApi.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ClientDiscoveryValueForSingleApi クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientDiscoveryValueForSingleApi (string name = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryDisplay display = null, string origin = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForProperties properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryDisplay display, string origin, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryValueForSingleApi.#ctor(System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryDisplay,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional display As ClientDiscoveryDisplay = null, Optional origin As String = null, Optional properties As ClientDiscoveryForProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryValueForSingleApi : string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryDisplay * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForProperties -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryValueForSingleApi" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryValueForSingleApi (name, display, origin, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="display" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryDisplay" />
        <Parameter Name="origin" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForProperties" />
      </Parameters>
      <Docs>
        <param name="name">name</param>
        <param name="display">この特定の操作のローカライズされた表示情報が含まれています</param>
        <param name="origin">操作の目的の実行子の RBAC UX と UX の監査ログで、操作の表示の制御</param>
        <param name="properties">[プロパティ]</param>
        <summary>
            ClientDiscoveryValueForSingleApi クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Display">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryDisplay Display { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryDisplay Display" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryValueForSingleApi.Display" />
      <MemberSignature Language="VB.NET" Value="Public Property Display As ClientDiscoveryDisplay" />
      <MemberSignature Language="F#" Value="member this.Display : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryDisplay with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryValueForSingleApi.Display" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Display")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryDisplay</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、この特定の操作のローカライズされた表示情報が含まれています
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryValueForSingleApi.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryValueForSingleApi.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の名前
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Origin">
      <MemberSignature Language="C#" Value="public string Origin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Origin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryValueForSingleApi.Origin" />
      <MemberSignature Language="VB.NET" Value="Public Property Origin As String" />
      <MemberSignature Language="F#" Value="member this.Origin : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryValueForSingleApi.Origin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Origin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定操作の目的の実行子以外の場合は、RBAC UX と UX の監査ログで、処理の表示を制御
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryValueForSingleApi.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As ClientDiscoveryForProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForProperties with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryValueForSingleApi.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のプロパティ
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>