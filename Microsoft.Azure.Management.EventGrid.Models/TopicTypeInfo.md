<Type Name="TopicTypeInfo" FullName="Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo">
  <TypeSignature Language="C#" Value="public class TopicTypeInfo : Microsoft.Azure.Management.EventGrid.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TopicTypeInfo extends Microsoft.Azure.Management.EventGrid.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class TopicTypeInfo&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type TopicTypeInfo = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.EventGrid.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            トピックのプロパティは、情報を入力します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicTypeInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            TopicTypeInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicTypeInfo (string id = null, string name = null, string type = null, string provider = null, string displayName = null, string description = null, string resourceRegionType = null, string provisioningState = null, System.Collections.Generic.IList&lt;string&gt; supportedLocations = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string provider, string displayName, string description, string resourceRegionType, string provisioningState, class System.Collections.Generic.IList`1&lt;string&gt; supportedLocations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional provider As String = null, Optional displayName As String = null, Optional description As String = null, Optional resourceRegionType As String = null, Optional provisioningState As String = null, Optional supportedLocations As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo : string * string * string * string * string * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo" Usage="new Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo (id, name, type, provider, displayName, description, resourceRegionType, provisioningState, supportedLocations)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="resourceRegionType" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="supportedLocations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id">リソースの完全修飾識別子</param>
        <param name="name">リソースの名前</param>
        <param name="type">リソースの種類</param>
        <param name="provider">トピックの種類のプロバイダーの Namespace です。</param>
        <param name="displayName">トピックの種類の表示名。</param>
        <param name="description">トピックの種類の説明です。</param>
        <param name="resourceRegionType">リソースの領域の種類。
            使用可能な値が含まれます: 'RegionalResource'、'GlobalResource'</param>
        <param name="provisioningState">トピックの種類のプロビジョニング状態。 使用可能な値が含まれます: '作成中'、'更新'、'削除'、'成功'、'キャンセル', '失敗'</param>
        <param name="supportedLocations">このトピックの種類でサポートされる場所の一覧です。</param>
        <summary>
            TopicTypeInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトピックの種類の説明を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、トピックの種類の名前を表示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.Provider" />
      <MemberSignature Language="VB.NET" Value="Public Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトピックの種類のプロバイダーの名前空間を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトピックの種類のプロビジョニング状態を設定します。 使用可能な値が含まれます: '作成中'、'更新'、'削除'、'成功'、'キャンセル', '失敗'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceRegionType">
      <MemberSignature Language="C#" Value="public string ResourceRegionType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceRegionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.ResourceRegionType" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceRegionType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceRegionType : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.ResourceRegionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceRegionType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソースの領域の種類を設定します。 使用可能な値が含まれます: 'RegionalResource'、'GlobalResource'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedLocations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SupportedLocations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SupportedLocations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.SupportedLocations" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportedLocations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SupportedLocations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.SupportedLocations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.supportedLocations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのトピックの種類でサポートされる場所の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>