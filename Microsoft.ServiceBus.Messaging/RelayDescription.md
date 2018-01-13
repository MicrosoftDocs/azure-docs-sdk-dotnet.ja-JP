<Type Name="RelayDescription" FullName="Microsoft.ServiceBus.Messaging.RelayDescription">
  <TypeSignature Language="C#" Value="public class RelayDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RelayDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.RelayDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class RelayDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type RelayDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.EntityDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="RelayDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>リレーの説明を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayDescription (string relayPath, Microsoft.ServiceBus.RelayType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string relayPath, valuetype Microsoft.ServiceBus.RelayType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RelayDescription.#ctor(System.String,Microsoft.ServiceBus.RelayType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (relayPath As String, type As RelayType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.RelayDescription : string * Microsoft.ServiceBus.RelayType -&gt; Microsoft.ServiceBus.Messaging.RelayDescription" Usage="new Microsoft.ServiceBus.Messaging.RelayDescription (relayPath, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="relayPath" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.ServiceBus.RelayType" />
      </Parameters>
      <Docs>
        <param name="relayPath">リレーのパス。</param>
        <param name="type">リレー型です。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authorization As AuthorizationRules" />
      <MemberSignature Language="F#" Value="member this.Authorization : Microsoft.ServiceBus.Messaging.AuthorizationRules" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.AuthorizationRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" /> を取得します。</summary>
        <value><see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" />。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionName">
      <MemberSignature Language="C#" Value="public string CollectionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CollectionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.CollectionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionName As String" />
      <MemberSignature Language="F#" Value="member this.CollectionName : string" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.CollectionName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceBus.Messaging.IResourceDescription.CollectionName</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはリレーに関連付けられているコレクションの名前を設定します。</summary>
        <value>リレーに関連付けられているコレクションの名前。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはリレーが作成された正確な時刻を設定します。</summary>
        <value>正確な時間、リレーが作成されました。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはリレーが動的かどうかを設定します。</summary>
        <value>リレーは動的; 場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenerCount">
      <MemberSignature Language="C#" Value="public int ListenerCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ListenerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.ListenerCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListenerCount As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenerCount : int" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.ListenerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはこのリレー リスナー数を設定します。</summary>
        <value>このリレーにリスナーの数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはリレーのパスを設定します。</summary>
        <value>リレーのパス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayType RelayType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayType RelayType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.RelayType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayType As RelayType" />
      <MemberSignature Language="F#" Value="member this.RelayType : Microsoft.ServiceBus.RelayType with get, set" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.RelayType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはリレーの種類を設定します。</summary>
        <value>リレー型です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresClientAuthorization">
      <MemberSignature Language="C#" Value="public bool RequiresClientAuthorization { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresClientAuthorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.RequiresClientAuthorization" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresClientAuthorization As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresClientAuthorization : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.RequiresClientAuthorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはこのリレーのクライアントの承認が必要かどうかを設定します。</summary>
        <value>このリレー; クライアントの承認が必要な場合は trueそれ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresTransportSecurity">
      <MemberSignature Language="C#" Value="public bool RequiresTransportSecurity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresTransportSecurity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.RequiresTransportSecurity" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresTransportSecurity As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresTransportSecurity : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.RequiresTransportSecurity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはこのリレーのトランスポート セキュリティが必要かどうかを設定します。</summary>
        <value>トランスポート セキュリティは、このリレー; に必要な場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはリレーが更新されたときに日付を設定します。</summary>
        <value>リレーが更新された日付。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはこのインスタンスに関連付けられているユーザーのメタデータを設定します。</summary>
        <value>このインスタンスに関連付けられているユーザーのメタデータ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>