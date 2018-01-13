<Type Name="EventType" FullName="Microsoft.Azure.Management.EventGrid.Models.EventType">
  <TypeSignature Language="C#" Value="public class EventType : Microsoft.Azure.Management.EventGrid.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventType extends Microsoft.Azure.Management.EventGrid.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.Models.EventType" />
  <TypeSignature Language="VB.NET" Value="Public Class EventType&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type EventType = class&#xA;    inherit Resource" />
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
            トピック サブジェクトのイベントの種類
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventType ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.EventType.#ctor" />
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
            EventType クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventType (string id = null, string name = null, string type = null, string displayName = null, string description = null, string schemaUrl = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string displayName, string description, string schemaUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.EventType.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional displayName As String = null, Optional description As String = null, Optional schemaUrl As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventGrid.Models.EventType : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.EventGrid.Models.EventType" Usage="new Microsoft.Azure.Management.EventGrid.Models.EventType (id, name, type, displayName, description, schemaUrl)" />
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
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="schemaUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソースの完全修飾識別子</param>
        <param name="name">リソースの名前</param>
        <param name="type">リソースの種類</param>
        <param name="displayName">イベントの種類の名前を表示します。</param>
        <param name="description">イベントの種類の説明です。</param>
        <param name="schemaUrl">このイベントの種類のスキーマの Url です。</param>
        <summary>
            EventType クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventType.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventType.Description" />
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
            取得またはイベントの種類の説明を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventType.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventType.DisplayName" />
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
            取得またはイベントの種類の表示名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchemaUrl">
      <MemberSignature Language="C#" Value="public string SchemaUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SchemaUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventType.SchemaUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property SchemaUrl As String" />
      <MemberSignature Language="F#" Value="member this.SchemaUrl : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventType.SchemaUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.schemaUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのイベントの種類のスキーマの url を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>