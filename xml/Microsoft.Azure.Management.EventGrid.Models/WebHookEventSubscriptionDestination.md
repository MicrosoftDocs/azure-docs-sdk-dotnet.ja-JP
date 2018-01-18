<Type Name="WebHookEventSubscriptionDestination" FullName="Microsoft.Azure.Management.EventGrid.Models.WebHookEventSubscriptionDestination">
  <TypeSignature Language="C#" Value="public class WebHookEventSubscriptionDestination : Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebHookEventSubscriptionDestination extends Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.Models.WebHookEventSubscriptionDestination" />
  <TypeSignature Language="VB.NET" Value="Public Class WebHookEventSubscriptionDestination&#xA;Inherits EventSubscriptionDestination" />
  <TypeSignature Language="F#" Value="type WebHookEventSubscriptionDestination = class&#xA;    inherit EventSubscriptionDestination" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("WebHook")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="b94a2-101">Webhook の宛先をイベントのサブスクリプションに関する情報</span><span class="sxs-lookup"><span data-stu-id="b94a2-101">Information about the webhook destination for an event subscription</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebHookEventSubscriptionDestination ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.WebHookEventSubscriptionDestination.#ctor" />
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
            <span data-ttu-id="b94a2-102">WebHookEventSubscriptionDestination クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b94a2-102">Initializes a new instance of the WebHookEventSubscriptionDestination class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebHookEventSubscriptionDestination (string endpointUrl = null, string endpointBaseUrl = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpointUrl, string endpointBaseUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.WebHookEventSubscriptionDestination.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional endpointUrl As String = null, Optional endpointBaseUrl As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventGrid.Models.WebHookEventSubscriptionDestination : string * string -&gt; Microsoft.Azure.Management.EventGrid.Models.WebHookEventSubscriptionDestination" Usage="new Microsoft.Azure.Management.EventGrid.Models.WebHookEventSubscriptionDestination (endpointUrl, endpointBaseUrl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpointUrl" Type="System.String" />
        <Parameter Name="endpointBaseUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointUrl"><span data-ttu-id="b94a2-103">イベント サブスクリプションの送信先のエンドポイントを表す URL。</span><span class="sxs-lookup"><span data-stu-id="b94a2-103">The URL that represents the endpoint of the destination of an event subscription.</span></span></param>
        <param name="endpointBaseUrl"><span data-ttu-id="b94a2-104">イベント サブスクリプションの送信先のエンドポイントを表す基本 URL です。</span><span class="sxs-lookup"><span data-stu-id="b94a2-104">The base URL that represents the endpoint of the destination of an event subscription.</span></span></param>
        <summary>
            <span data-ttu-id="b94a2-105">WebHookEventSubscriptionDestination クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b94a2-105">Initializes a new instance of the WebHookEventSubscriptionDestination class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointBaseUrl">
      <MemberSignature Language="C#" Value="public string EndpointBaseUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndpointBaseUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.WebHookEventSubscriptionDestination.EndpointBaseUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndpointBaseUrl As String" />
      <MemberSignature Language="F#" Value="member this.EndpointBaseUrl : string" Usage="Microsoft.Azure.Management.EventGrid.Models.WebHookEventSubscriptionDestination.EndpointBaseUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpointBaseUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b94a2-106">イベント サブスクリプションの送信先のエンドポイントを表す基本 URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="b94a2-106">Gets the base URL that represents the endpoint of the destination of an event subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointUrl">
      <MemberSignature Language="C#" Value="public string EndpointUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndpointUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.WebHookEventSubscriptionDestination.EndpointUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointUrl As String" />
      <MemberSignature Language="F#" Value="member this.EndpointUrl : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.WebHookEventSubscriptionDestination.EndpointUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpointUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b94a2-107">取得またはイベントのサブスクリプションの送信先のエンドポイントを表す URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="b94a2-107">Gets or sets the URL that represents the endpoint of the destination of an event subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>