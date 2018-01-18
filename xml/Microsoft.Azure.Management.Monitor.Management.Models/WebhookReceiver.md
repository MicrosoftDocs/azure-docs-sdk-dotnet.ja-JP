<Type Name="WebhookReceiver" FullName="Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver">
  <TypeSignature Language="C#" Value="public class WebhookReceiver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebhookReceiver extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver" />
  <TypeSignature Language="VB.NET" Value="Public Class WebhookReceiver" />
  <TypeSignature Language="F#" Value="type WebhookReceiver = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f2211-101">Webhook 受信者です。</span><span class="sxs-lookup"><span data-stu-id="f2211-101">A webhook receiver.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebhookReceiver ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f2211-102">WebhookReceiver クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f2211-102">Initializes a new instance of the WebhookReceiver class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebhookReceiver (string name, string serviceUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string serviceUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, serviceUri As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver : string * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver (name, serviceUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="serviceUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="f2211-103">Webhook の受信者の名前。</span><span class="sxs-lookup"><span data-stu-id="f2211-103">The name of the webhook receiver.</span></span> <span data-ttu-id="f2211-104">名前は、アクション グループ内の全受信者の間で一意である必要があります。</span><span class="sxs-lookup"><span data-stu-id="f2211-104">Names must be unique across all receivers within an action group.</span></span></param>
        <param name="serviceUri"><span data-ttu-id="f2211-105">Webhook を送信する URI。</span><span class="sxs-lookup"><span data-stu-id="f2211-105">The URI where webhooks should be sent.</span></span></param>
        <summary>
            <span data-ttu-id="f2211-106">WebhookReceiver クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f2211-106">Initializes a new instance of the WebhookReceiver class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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
            <span data-ttu-id="f2211-107">取得または webhook 受信者の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="f2211-107">Gets or sets the name of the webhook receiver.</span></span> <span data-ttu-id="f2211-108">名前は、アクション グループ内の全受信者の間で一意である必要があります。</span><span class="sxs-lookup"><span data-stu-id="f2211-108">Names must be unique across all receivers within an action group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceUri">
      <MemberSignature Language="C#" Value="public string ServiceUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver.ServiceUri" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceUri As String" />
      <MemberSignature Language="F#" Value="member this.ServiceUri : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver.ServiceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2211-109">取得または webhook を送信する URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="f2211-109">Gets or sets the URI where webhooks should be sent.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.WebhookReceiver.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="webhookReceiver.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f2211-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f2211-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f2211-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f2211-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>