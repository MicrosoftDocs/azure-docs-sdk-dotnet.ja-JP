<Type Name="RuleWebhookAction" FullName="Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction">
  <TypeSignature Language="C#" Value="public class RuleWebhookAction : Microsoft.Azure.Management.Monitor.Management.Models.RuleAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RuleWebhookAction extends Microsoft.Azure.Management.Monitor.Management.Models.RuleAction" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction" />
  <TypeSignature Language="VB.NET" Value="Public Class RuleWebhookAction&#xA;Inherits RuleAction" />
  <TypeSignature Language="F#" Value="type RuleWebhookAction = class&#xA;    inherit RuleAction" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Monitor.Management.Models.RuleAction</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Azure.Management.Insights.Models.RuleWebhookAction")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="bc9e5-101">ルールの条件が評価されるときに、サービスに投稿するアクションを指定します。</span><span class="sxs-lookup"><span data-stu-id="bc9e5-101">Specifies the action to post to service when the rule condition is evaluated.</span></span> <span data-ttu-id="bc9e5-102">識別子は常に RuleWebhookAction ここでです。</span><span class="sxs-lookup"><span data-stu-id="bc9e5-102">The discriminator is always RuleWebhookAction in this case.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleWebhookAction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction.#ctor" />
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
            <span data-ttu-id="bc9e5-103">RuleWebhookAction クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bc9e5-103">Initializes a new instance of the RuleWebhookAction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleWebhookAction (string serviceUri = null, System.Collections.Generic.IDictionary&lt;string,string&gt; properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceUri, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction.#ctor(System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceUri As String = null, Optional properties As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction : string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction (serviceUri, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.String" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceUri"><span data-ttu-id="bc9e5-104">アラートがアクティブ化や解決時に、通知をポストするサービスの uri。</span><span class="sxs-lookup"><span data-stu-id="bc9e5-104">the service uri to Post the notification when the alert activates or resolves.</span></span></param>
        <param name="properties"><span data-ttu-id="bc9e5-105">post 操作に含めるカスタム プロパティのディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="bc9e5-105">the dictionary of custom properties to include with the post operation.</span></span> <span data-ttu-id="bc9e5-106">Webhook ペイロードには、これらのデータが追加されます。</span><span class="sxs-lookup"><span data-stu-id="bc9e5-106">These data are appended to the webhook payload.</span></span></param>
        <summary>
            <span data-ttu-id="bc9e5-107">RuleWebhookAction クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bc9e5-107">Initializes a new instance of the RuleWebhookAction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bc9e5-108">取得または post 操作に含めるカスタム プロパティのディクショナリを設定します。</span><span class="sxs-lookup"><span data-stu-id="bc9e5-108">Gets or sets the dictionary of custom properties to include with the post operation.</span></span> <span data-ttu-id="bc9e5-109">Webhook ペイロードには、これらのデータが追加されます。</span><span class="sxs-lookup"><span data-stu-id="bc9e5-109">These data are appended to the webhook payload.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceUri">
      <MemberSignature Language="C#" Value="public string ServiceUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction.ServiceUri" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceUri As String" />
      <MemberSignature Language="F#" Value="member this.ServiceUri : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RuleWebhookAction.ServiceUri" />
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
            <span data-ttu-id="bc9e5-110">取得またはアラートがアクティブ化や解決時に、通知をポストするサービスの uri を設定します。</span><span class="sxs-lookup"><span data-stu-id="bc9e5-110">Gets or sets the service uri to Post the notification when the alert activates or resolves.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>