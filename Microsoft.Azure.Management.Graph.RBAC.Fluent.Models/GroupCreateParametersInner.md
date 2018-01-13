<Type Name="GroupCreateParametersInner" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner">
  <TypeSignature Language="C#" Value="public class GroupCreateParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi GroupCreateParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class GroupCreateParametersInner" />
  <TypeSignature Language="F#" Value="type GroupCreateParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="60f02-101">新しいグループを作成するためのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="60f02-101">Request parameters for creating a new group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GroupCreateParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="60f02-102">GroupCreateParametersInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="60f02-102">Initializes a new instance of the GroupCreateParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GroupCreateParametersInner (string displayName, string mailNickname);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string displayName, string mailNickname) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (displayName As String, mailNickname As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner : string * string -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner (displayName, mailNickname)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="mailNickname" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="displayName"><span data-ttu-id="60f02-103">グループの表示名</span><span class="sxs-lookup"><span data-stu-id="60f02-103">Group display name</span></span></param>
        <param name="mailNickname"><span data-ttu-id="60f02-104">メールのニックネーム</span><span class="sxs-lookup"><span data-stu-id="60f02-104">Mail nickname</span></span></param>
        <summary>
            <span data-ttu-id="60f02-105">GroupCreateParametersInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="60f02-105">Initializes a new instance of the GroupCreateParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f02-106">取得または設定グループの表示名</span><span class="sxs-lookup"><span data-stu-id="60f02-106">Gets or sets group display name</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MailEnabled">
      <MemberSignature Language="C#" Value="public static bool MailEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property bool MailEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner.MailEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MailEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.MailEnabled : bool" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner.MailEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mailEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f02-107">かどうか、グループで、メールが有効にします。</span><span class="sxs-lookup"><span data-stu-id="60f02-107">Whether the group is mail-enabled.</span></span> <span data-ttu-id="60f02-108">false のみ有効です。</span><span class="sxs-lookup"><span data-stu-id="60f02-108">Must be false.</span></span> <span data-ttu-id="60f02-109">これは、Graph API を使用して純粋なセキュリティ グループのみを作成できるためです。</span><span class="sxs-lookup"><span data-stu-id="60f02-109">This is because only pure security groups can be created using the Graph API.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MailNickname">
      <MemberSignature Language="C#" Value="public string MailNickname { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MailNickname" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner.MailNickname" />
      <MemberSignature Language="VB.NET" Value="Public Property MailNickname As String" />
      <MemberSignature Language="F#" Value="member this.MailNickname : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner.MailNickname" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mailNickname")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f02-110">取得またはメールのニックネームの設定</span><span class="sxs-lookup"><span data-stu-id="60f02-110">Gets or sets mail nickname</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityEnabled">
      <MemberSignature Language="C#" Value="public static bool SecurityEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property bool SecurityEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner.SecurityEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property SecurityEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.SecurityEnabled : bool" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner.SecurityEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="securityEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f02-111">かどうか、グループは、セキュリティ グループです。</span><span class="sxs-lookup"><span data-stu-id="60f02-111">Whether the group is a security group.</span></span> <span data-ttu-id="60f02-112">True にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="60f02-112">Must be true.</span></span> <span data-ttu-id="60f02-113">これは、Graph API を使用して純粋なセキュリティ グループのみを作成できるためです。</span><span class="sxs-lookup"><span data-stu-id="60f02-113">This is because only pure security groups can be created using the Graph API.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="groupCreateParametersInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="60f02-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="60f02-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="60f02-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="60f02-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>