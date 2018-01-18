<Type Name="AuthorizationRule" FullName="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule">
  <TypeSignature Language="C#" Value="public abstract class AuthorizationRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit AuthorizationRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class AuthorizationRule" />
  <TypeSignature Language="F#" Value="type AuthorizationRule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.Messaging.AllowRule))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.Messaging.SharedAccessAuthorizationRule))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="427a5-101">操作が許可されるかどうかを判定するために使用した Azure Service Bus 承認規則を定義します。</span><span class="sxs-lookup"><span data-stu-id="427a5-101">Defines the Azure Service Bus authorization rule that is used to determine whether an operation is permissible or not.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ClaimType">
      <MemberSignature Language="C#" Value="public string ClaimType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClaimType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ClaimType" />
      <MemberSignature Language="VB.NET" Value="Public Property ClaimType As String" />
      <MemberSignature Language="F#" Value="member this.ClaimType : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ClaimType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="427a5-102">クレームの種類を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="427a5-102">Gets or sets the claim type.</span></span></summary>
        <value><span data-ttu-id="427a5-103">要求の種類。</span><span class="sxs-lookup"><span data-stu-id="427a5-103">The claim type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClaimValue">
      <MemberSignature Language="C#" Value="public string ClaimValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClaimValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ClaimValue" />
      <MemberSignature Language="VB.NET" Value="Public Property ClaimValue As String" />
      <MemberSignature Language="F#" Value="member this.ClaimValue : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ClaimValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="427a5-104">取得または要求の値は、'Send'、'Listen' か 'の管理 を設定します。</span><span class="sxs-lookup"><span data-stu-id="427a5-104">Gets or sets the claim value which is either ‘Send’, ‘Listen’, or ‘Manage’.</span></span></summary>
        <value><span data-ttu-id="427a5-105">'Send'、'Listen' か 'を ' 管理要求の値。</span><span class="sxs-lookup"><span data-stu-id="427a5-105">The claim value which is either ‘Send’, ‘Listen’, or ‘Manage’.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Clone () As AuthorizationRule" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&#xA;override this.Clone : unit -&gt; Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" Usage="authorizationRule.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="427a5-106">コピーを作成<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />です。</span><span class="sxs-lookup"><span data-stu-id="427a5-106">Creates a copy of <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />.</span></span></summary>
        <returns><span data-ttu-id="427a5-107">作成されたのコピー<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />です。</span><span class="sxs-lookup"><span data-stu-id="427a5-107">A created copy of <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedTime">
      <MemberSignature Language="C#" Value="public DateTime CreatedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.CreatedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedTime : DateTime" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.CreatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Order=1006)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="427a5-108">取得または日付と時刻の承認規則の作成時に設定します。</span><span class="sxs-lookup"><span data-stu-id="427a5-108">Gets or sets the date and time when the authorization rule was created.</span></span></summary>
        <value><span data-ttu-id="427a5-109">日時の承認規則の作成時にします。</span><span class="sxs-lookup"><span data-stu-id="427a5-109">The date and time when the authorization rule was created.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="authorizationRule.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="427a5-110">現在のオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="427a5-110">The object to compare with the current object.</span></span></param>
        <summary><span data-ttu-id="427a5-111">指定したオブジェクトが、現在のオブジェクトと等しいかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="427a5-111">Determines whether the specified object is equal to the current object.</span></span></summary>
        <returns><span data-ttu-id="427a5-112">指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="427a5-112">true if the specified object is equal to the current object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="authorizationRule.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="427a5-113">このインスタンスのハッシュ コードを返します。</span><span class="sxs-lookup"><span data-stu-id="427a5-113">Returns the hash code for this instance.</span></span></summary>
        <returns><span data-ttu-id="427a5-114">対象のインスタンスのハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="427a5-114">The hash code for this instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssuerName">
      <MemberSignature Language="C#" Value="public string IssuerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IssuerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.IssuerName" />
      <MemberSignature Language="VB.NET" Value="Public Property IssuerName As String" />
      <MemberSignature Language="F#" Value="member this.IssuerName : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.IssuerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="427a5-115">取得または発行者の名前の識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="427a5-115">Gets or sets the name identifier of the issuer.</span></span></summary>
        <value><span data-ttu-id="427a5-116">発行者の名前の識別子。</span><span class="sxs-lookup"><span data-stu-id="427a5-116">The name identifier of the issuer.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public abstract string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="427a5-117">取得または承認規則のキー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="427a5-117">Gets or sets the authorization rule key name.</span></span></summary>
        <value><span data-ttu-id="427a5-118">承認規則のキー名。</span><span class="sxs-lookup"><span data-stu-id="427a5-118">The authorization rule key name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifiedTime">
      <MemberSignature Language="C#" Value="public DateTime ModifiedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ModifiedTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.ModifiedTime : DateTime" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Order=1007)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="427a5-119">取得または日付と時刻の承認規則が変更された日時を設定します。</span><span class="sxs-lookup"><span data-stu-id="427a5-119">Gets or sets the date and time when the authorization rule was modified.</span></span></summary>
        <value><span data-ttu-id="427a5-120">日付と、承認規則が変更された日時。</span><span class="sxs-lookup"><span data-stu-id="427a5-120">The date and time when the authorization rule was modified.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameIdentifierClaimType">
      <MemberSignature Language="C#" Value="public const string NameIdentifierClaimType;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string NameIdentifierClaimType" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.NameIdentifierClaimType" />
      <MemberSignature Language="VB.NET" Value="Public Const NameIdentifierClaimType As String " />
      <MemberSignature Language="F#" Value="val mutable NameIdentifierClaimType : string" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.NameIdentifierClaimType" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="427a5-121">名前識別子要求の規則。</span><span class="sxs-lookup"><span data-stu-id="427a5-121">The name identifier claim rule.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidate">
      <MemberSignature Language="C#" Value="protected virtual void OnValidate ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnValidate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.OnValidate" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnValidate ()" />
      <MemberSignature Language="F#" Value="abstract member OnValidate : unit -&gt; unit&#xA;override this.OnValidate : unit -&gt; unit" Usage="authorizationRule.OnValidate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="427a5-122">有効では、承認規則を検証するときに、カスタム ハンドリングを提供するクラスを派生します。</span><span class="sxs-lookup"><span data-stu-id="427a5-122">Enables derived classes to provide custom handling when validating the authorization rule.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Revision">
      <MemberSignature Language="C#" Value="public long Revision { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Revision" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.Revision" />
      <MemberSignature Language="VB.NET" Value="Public Property Revision As Long" />
      <MemberSignature Language="F#" Value="member this.Revision : int64 with get, set" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.Revision" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Order=1008)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="427a5-123">取得または変更リビジョン番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="427a5-123">Gets or sets the modification revision number.</span></span></summary>
        <value><span data-ttu-id="427a5-124">変更リビジョン番号。</span><span class="sxs-lookup"><span data-stu-id="427a5-124">The modification revision number.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rights">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.Messaging.AccessRights&gt; Rights { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.Azure.NotificationHubs.Messaging.AccessRights&gt; Rights" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.Rights" />
      <MemberSignature Language="VB.NET" Value="Public Property Rights As IEnumerable(Of AccessRights)" />
      <MemberSignature Language="F#" Value="member this.Rights : seq&lt;Microsoft.Azure.NotificationHubs.Messaging.AccessRights&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.Rights" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.Messaging.AccessRights&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="427a5-125">取得または権限の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="427a5-125">Gets or sets the list of rights.</span></span></summary>
        <value><span data-ttu-id="427a5-126">権限の一覧。</span><span class="sxs-lookup"><span data-stu-id="427a5-126">The list of rights.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RoleClaimType">
      <MemberSignature Language="C#" Value="public const string RoleClaimType;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string RoleClaimType" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.RoleClaimType" />
      <MemberSignature Language="VB.NET" Value="Public Const RoleClaimType As String " />
      <MemberSignature Language="F#" Value="val mutable RoleClaimType : string" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.RoleClaimType" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="427a5-127">ロール クレーム ルール。</span><span class="sxs-lookup"><span data-stu-id="427a5-127">The role claim rule.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RoleRoleClaimType">
      <MemberSignature Language="C#" Value="public const string RoleRoleClaimType;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string RoleRoleClaimType" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.RoleRoleClaimType" />
      <MemberSignature Language="VB.NET" Value="Public Const RoleRoleClaimType As String " />
      <MemberSignature Language="F#" Value="val mutable RoleRoleClaimType : string" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.RoleRoleClaimType" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="427a5-128">役割の役割の要求規則。</span><span class="sxs-lookup"><span data-stu-id="427a5-128">The role role claim rule.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKeyClaimType">
      <MemberSignature Language="C#" Value="public const string SharedAccessKeyClaimType;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SharedAccessKeyClaimType" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.SharedAccessKeyClaimType" />
      <MemberSignature Language="VB.NET" Value="Public Const SharedAccessKeyClaimType As String " />
      <MemberSignature Language="F#" Value="val mutable SharedAccessKeyClaimType : string" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.SharedAccessKeyClaimType" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="427a5-129">共有アクセス キーは、ルールを要求します。</span><span class="sxs-lookup"><span data-stu-id="427a5-129">The shared access key claim rule.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShortNameIdentifierClaimType">
      <MemberSignature Language="C#" Value="public const string ShortNameIdentifierClaimType;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ShortNameIdentifierClaimType" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ShortNameIdentifierClaimType" />
      <MemberSignature Language="VB.NET" Value="Public Const ShortNameIdentifierClaimType As String " />
      <MemberSignature Language="F#" Value="val mutable ShortNameIdentifierClaimType : string" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ShortNameIdentifierClaimType" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="427a5-130">短い名前識別子は、ルールを要求します。</span><span class="sxs-lookup"><span data-stu-id="427a5-130">The short name identifier claim rule.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShortUpnClaimType">
      <MemberSignature Language="C#" Value="public const string ShortUpnClaimType;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ShortUpnClaimType" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ShortUpnClaimType" />
      <MemberSignature Language="VB.NET" Value="Public Const ShortUpnClaimType As String " />
      <MemberSignature Language="F#" Value="val mutable ShortUpnClaimType : string" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ShortUpnClaimType" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="427a5-131">規則の短い UPN 要求します。</span><span class="sxs-lookup"><span data-stu-id="427a5-131">The short UPN claim rule.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpnClaimType">
      <MemberSignature Language="C#" Value="public const string UpnClaimType;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string UpnClaimType" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.UpnClaimType" />
      <MemberSignature Language="VB.NET" Value="Public Const UpnClaimType As String " />
      <MemberSignature Language="F#" Value="val mutable UpnClaimType : string" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.UpnClaimType" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="427a5-132">UPN 要求規則。</span><span class="sxs-lookup"><span data-stu-id="427a5-132">The UPN claim rule.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateRights">
      <MemberSignature Language="C#" Value="protected virtual void ValidateRights (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.Messaging.AccessRights&gt; value);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void ValidateRights(class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.Azure.NotificationHubs.Messaging.AccessRights&gt; value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ValidateRights(System.Collections.Generic.IEnumerable{Microsoft.Azure.NotificationHubs.Messaging.AccessRights})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub ValidateRights (value As IEnumerable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="abstract member ValidateRights : seq&lt;Microsoft.Azure.NotificationHubs.Messaging.AccessRights&gt; -&gt; unit&#xA;override this.ValidateRights : seq&lt;Microsoft.Azure.NotificationHubs.Messaging.AccessRights&gt; -&gt; unit" Usage="authorizationRule.ValidateRights value" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.Messaging.AccessRights&gt;" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="427a5-133">確認へのアクセス権。</span><span class="sxs-lookup"><span data-stu-id="427a5-133">The access rights to check.</span></span></param>
        <summary><span data-ttu-id="427a5-134">指定したアクセス権の有効性を確認します。</span><span class="sxs-lookup"><span data-stu-id="427a5-134">Checks the validity of the specified access rights.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>