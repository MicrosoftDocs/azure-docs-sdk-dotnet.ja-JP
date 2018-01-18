<Type Name="SenderAuthorization" FullName="Microsoft.Azure.Management.Monitor.Models.SenderAuthorization">
  <TypeSignature Language="C#" Value="public class SenderAuthorization" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SenderAuthorization extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Models.SenderAuthorization" />
  <TypeSignature Language="VB.NET" Value="Public Class SenderAuthorization" />
  <TypeSignature Language="F#" Value="type SenderAuthorization = class" />
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
            <span data-ttu-id="e2952-101">このイベントの原因となった操作が実行したユーザーによって使用される承認します。</span><span class="sxs-lookup"><span data-stu-id="e2952-101">the authorization used by the user who has performed the operation that led to this event.</span></span> <span data-ttu-id="e2952-102">これは、イベントの RBAC プロパティをキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="e2952-102">This captures the RBAC properties of the event.</span></span>
            <span data-ttu-id="e2952-103">'Action'、'ロール' および 'scope' 通常が含まれます</span><span class="sxs-lookup"><span data-stu-id="e2952-103">These usually include the 'action', 'role' and the 'scope'</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SenderAuthorization ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.SenderAuthorization.#ctor" />
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
            <span data-ttu-id="e2952-104">SenderAuthorization クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e2952-104">Initializes a new instance of the SenderAuthorization class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SenderAuthorization (string action = null, string role = null, string scope = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string action, string role, string scope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.SenderAuthorization.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional action As String = null, Optional role As String = null, Optional scope As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Models.SenderAuthorization : string * string * string -&gt; Microsoft.Azure.Management.Monitor.Models.SenderAuthorization" Usage="new Microsoft.Azure.Management.Monitor.Models.SenderAuthorization (action, role, scope)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="role" Type="System.String" />
        <Parameter Name="scope" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="action"><span data-ttu-id="e2952-105">許可されたアクション。</span><span class="sxs-lookup"><span data-stu-id="e2952-105">the permissible actions.</span></span> <span data-ttu-id="e2952-106">インスタンス: microsoft.support/supporttickets/write</span><span class="sxs-lookup"><span data-stu-id="e2952-106">For instance: microsoft.support/supporttickets/write</span></span></param>
        <param name="role"><span data-ttu-id="e2952-107">ユーザーのロール。</span><span class="sxs-lookup"><span data-stu-id="e2952-107">the role of the user.</span></span> <span data-ttu-id="e2952-108">インスタンス: サブスクリプションの管理</span><span class="sxs-lookup"><span data-stu-id="e2952-108">For instance: Subscription Admin</span></span></param>
        <param name="scope"><span data-ttu-id="e2952-109">スコープです。</span><span class="sxs-lookup"><span data-stu-id="e2952-109">the scope.</span></span></param>
        <summary>
            <span data-ttu-id="e2952-110">SenderAuthorization クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e2952-110">Initializes a new instance of the SenderAuthorization class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public string Action { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.SenderAuthorization.Action" />
      <MemberSignature Language="VB.NET" Value="Public Property Action As String" />
      <MemberSignature Language="F#" Value="member this.Action : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.SenderAuthorization.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="action")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2952-111">取得または許可されたアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="e2952-111">Gets or sets the permissible actions.</span></span> <span data-ttu-id="e2952-112">インスタンス: microsoft.support/supporttickets/write</span><span class="sxs-lookup"><span data-stu-id="e2952-112">For instance: microsoft.support/supporttickets/write</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Role">
      <MemberSignature Language="C#" Value="public string Role { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Role" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.SenderAuthorization.Role" />
      <MemberSignature Language="VB.NET" Value="Public Property Role As String" />
      <MemberSignature Language="F#" Value="member this.Role : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.SenderAuthorization.Role" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="role")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2952-113">取得またはユーザーのロールを設定します。</span><span class="sxs-lookup"><span data-stu-id="e2952-113">Gets or sets the role of the user.</span></span> <span data-ttu-id="e2952-114">インスタンス: サブスクリプションの管理</span><span class="sxs-lookup"><span data-stu-id="e2952-114">For instance: Subscription Admin</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public string Scope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.SenderAuthorization.Scope" />
      <MemberSignature Language="VB.NET" Value="Public Property Scope As String" />
      <MemberSignature Language="F#" Value="member this.Scope : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.SenderAuthorization.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scope")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2952-115">取得またはスコープを設定します。</span><span class="sxs-lookup"><span data-stu-id="e2952-115">Gets or sets the scope.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>