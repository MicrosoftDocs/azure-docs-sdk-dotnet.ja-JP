<Type Name="ActivityLogAlertActionGroup" FullName="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup">
  <TypeSignature Language="C#" Value="public class ActivityLogAlertActionGroup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActivityLogAlertActionGroup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class ActivityLogAlertActionGroup" />
  <TypeSignature Language="F#" Value="type ActivityLogAlertActionGroup = class" />
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
            <span data-ttu-id="27726-101">Azure 操作グループへのポインター。</span><span class="sxs-lookup"><span data-stu-id="27726-101">A pointer to an Azure Action Group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityLogAlertActionGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup.#ctor" />
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
            <span data-ttu-id="27726-102">ActivityLogAlertActionGroup クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="27726-102">Initializes a new instance of the ActivityLogAlertActionGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityLogAlertActionGroup (string actionGroupId, System.Collections.Generic.IDictionary&lt;string,string&gt; webhookProperties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string actionGroupId, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; webhookProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup.#ctor(System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (actionGroupId As String, Optional webhookProperties As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup : string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup (actionGroupId, webhookProperties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actionGroupId" Type="System.String" />
        <Parameter Name="webhookProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="actionGroupId"><span data-ttu-id="27726-103">アクション グループの resourceId です。</span><span class="sxs-lookup"><span data-stu-id="27726-103">The resourceId of the action group.</span></span>
            <span data-ttu-id="27726-104">これは、null または空にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="27726-104">This cannot be null or empty.</span></span></param>
        <param name="webhookProperties"><span data-ttu-id="27726-105">post 操作に含めるカスタム プロパティのディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="27726-105">the dictionary of custom properties to include with the post operation.</span></span> <span data-ttu-id="27726-106">Webhook ペイロードには、これらのデータが追加されます。</span><span class="sxs-lookup"><span data-stu-id="27726-106">These data are appended to the webhook payload.</span></span></param>
        <summary>
            <span data-ttu-id="27726-107">ActivityLogAlertActionGroup クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="27726-107">Initializes a new instance of the ActivityLogAlertActionGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionGroupId">
      <MemberSignature Language="C#" Value="public string ActionGroupId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActionGroupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup.ActionGroupId" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionGroupId As String" />
      <MemberSignature Language="F#" Value="member this.ActionGroupId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup.ActionGroupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actionGroupId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27726-108">取得またはアクション グループの resourceId を設定します。</span><span class="sxs-lookup"><span data-stu-id="27726-108">Gets or sets the resourceId of the action group.</span></span> <span data-ttu-id="27726-109">これは、null または空にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="27726-109">This cannot be null or empty.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="activityLogAlertActionGroup.Validate " />
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
            <span data-ttu-id="27726-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="27726-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="27726-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="27726-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WebhookProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; WebhookProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; WebhookProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup.WebhookProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property WebhookProperties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.WebhookProperties : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertActionGroup.WebhookProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="webhookProperties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27726-112">取得または post 操作に含めるカスタム プロパティのディクショナリを設定します。</span><span class="sxs-lookup"><span data-stu-id="27726-112">Gets or sets the dictionary of custom properties to include with the post operation.</span></span> <span data-ttu-id="27726-113">Webhook ペイロードには、これらのデータが追加されます。</span><span class="sxs-lookup"><span data-stu-id="27726-113">These data are appended to the webhook payload.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>