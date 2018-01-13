<Type Name="RoutingServiceBusQueueEndpointProperties" FullName="Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties">
  <TypeSignature Language="C#" Value="public class RoutingServiceBusQueueEndpointProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RoutingServiceBusQueueEndpointProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class RoutingServiceBusQueueEndpointProperties" />
  <TypeSignature Language="F#" Value="type RoutingServiceBusQueueEndpointProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            サービス バス キューのエンドポイントの種類に関連するプロパティです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RoutingServiceBusQueueEndpointProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            RoutingServiceBusQueueEndpointProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RoutingServiceBusQueueEndpointProperties (string connectionString, string name, string subscriptionId = null, string resourceGroup = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string name, string subscriptionId, string resourceGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String, name As String, Optional subscriptionId As String = null, Optional resourceGroup As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties : string * string * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties" Usage="new Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties (connectionString, name, subscriptionId, resourceGroup)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="resourceGroup" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Service bus キュー エンドポイントの接続文字列。</param>
        <param name="name">このエンドポイントを識別する名前。 名前は文字の英数字、ピリオド、アンダー スコア、ハイフンのみを含めることができ、64 文字の最大長であります。 次の名前は予約されています。 イベント、operationsMonitoringEvents、fileNotifications、$default です。 エンドポイント名は、エンドポイントの種類で一意である必要があります。 名前を実際のキュー名と同じにする必要がありますはできません。</param>
        <param name="subscriptionId">Service bus キュー エンドポイントのサブスクリプションの識別子です。</param>
        <param name="resourceGroup">Service bus キュー エンドポイントのリソース グループの名前。</param>
        <summary>
            RoutingServiceBusQueueEndpointProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public string ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="connectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または service bus キュー エンドポイントの接続文字列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            取得または設定をこのエンドポイントを識別する名前。 名前は文字の英数字、ピリオド、アンダー スコア、ハイフンのみを含めることができ、64 文字の最大長であります。 次の名前は予約されています。 イベント、operationsMonitoringEvents、fileNotifications、$default です。 エンドポイント名は、エンドポイントの種類で一意である必要があります。 名前を実際のキュー名と同じにする必要がありますはできません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties.ResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または service bus キュー エンドポイントのリソース グループの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または service bus キュー エンドポイントのサブスクリプション識別子を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="routingServiceBusQueueEndpointProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>