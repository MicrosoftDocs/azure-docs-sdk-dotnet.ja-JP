<Type Name="RuleEmailAction" FullName="Microsoft.Azure.Management.Monitor.Management.Models.RuleEmailAction">
  <TypeSignature Language="C#" Value="public class RuleEmailAction : Microsoft.Azure.Management.Monitor.Management.Models.RuleAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RuleEmailAction extends Microsoft.Azure.Management.Monitor.Management.Models.RuleAction" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.RuleEmailAction" />
  <TypeSignature Language="VB.NET" Value="Public Class RuleEmailAction&#xA;Inherits RuleAction" />
  <TypeSignature Language="F#" Value="type RuleEmailAction = class&#xA;    inherit RuleAction" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Azure.Management.Insights.Models.RuleEmailAction")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="d2b51-101">ルールの条件が評価されるときに電子メールを送信するアクションを指定します。</span><span class="sxs-lookup"><span data-stu-id="d2b51-101">Specifies the action to send email when the rule condition is evaluated.</span></span> <span data-ttu-id="d2b51-102">識別子は常に RuleEmailAction ここでです。</span><span class="sxs-lookup"><span data-stu-id="d2b51-102">The discriminator is always RuleEmailAction in this case.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleEmailAction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RuleEmailAction.#ctor" />
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
            <span data-ttu-id="d2b51-103">RuleEmailAction クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d2b51-103">Initializes a new instance of the RuleEmailAction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleEmailAction (Nullable&lt;bool&gt; sendToServiceOwners = null, System.Collections.Generic.IList&lt;string&gt; customEmails = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; sendToServiceOwners, class System.Collections.Generic.IList`1&lt;string&gt; customEmails) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RuleEmailAction.#ctor(System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional sendToServiceOwners As Nullable(Of Boolean) = null, Optional customEmails As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.RuleEmailAction : Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.RuleEmailAction" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.RuleEmailAction (sendToServiceOwners, customEmails)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sendToServiceOwners" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customEmails" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="sendToServiceOwners"><span data-ttu-id="d2b51-104">かどうか、アラートがアクティブになると、サービスの管理者 (サービスとの共同管理者) に通知する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d2b51-104">Whether the administrators (service and co-administrators) of the service should be notified when the alert is activated.</span></span></param>
        <param name="customEmails"><span data-ttu-id="d2b51-105">アラートのアクティブ化を通知する管理者のカスタムの電子メール アドレスの一覧。</span><span class="sxs-lookup"><span data-stu-id="d2b51-105">the list of administrator's custom email addresses to notify of the activation of the alert.</span></span></param>
        <summary>
            <span data-ttu-id="d2b51-106">RuleEmailAction クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d2b51-106">Initializes a new instance of the RuleEmailAction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomEmails">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; CustomEmails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; CustomEmails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RuleEmailAction.CustomEmails" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomEmails As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.CustomEmails : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RuleEmailAction.CustomEmails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="customEmails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d2b51-107">取得またはアラートのアクティブ化を通知する管理者のカスタムの電子メール アドレスの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="d2b51-107">Gets or sets the list of administrator's custom email addresses to notify of the activation of the alert.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendToServiceOwners">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SendToServiceOwners { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SendToServiceOwners" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RuleEmailAction.SendToServiceOwners" />
      <MemberSignature Language="VB.NET" Value="Public Property SendToServiceOwners As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SendToServiceOwners : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RuleEmailAction.SendToServiceOwners" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sendToServiceOwners")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d2b51-108">取得またはサービスの管理者 (サービスとの共同管理者) は、アラートがアクティブになったときに通知するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="d2b51-108">Gets or sets whether the administrators (service and co-administrators) of the service should be notified when the alert is activated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>