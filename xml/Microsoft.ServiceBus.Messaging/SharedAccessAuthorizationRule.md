<Type Name="SharedAccessAuthorizationRule" FullName="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule">
  <TypeSignature Language="C#" Value="public class SharedAccessAuthorizationRule : Microsoft.ServiceBus.Messaging.AuthorizationRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedAccessAuthorizationRule extends Microsoft.ServiceBus.Messaging.AuthorizationRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedAccessAuthorizationRule&#xA;Inherits AuthorizationRule" />
  <TypeSignature Language="F#" Value="type SharedAccessAuthorizationRule = class&#xA;    inherit AuthorizationRule" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.AuthorizationRule</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="SharedAccessAuthorizationRule", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="f7212-101">共有アクセス操作の承認規則を定義します。</span><span class="sxs-lookup"><span data-stu-id="f7212-101">Defines the authorization rule for shared access operation.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAuthorizationRule (string keyName, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; rights);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyName, class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.ServiceBus.Messaging.AccessRights&gt; rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.#ctor(System.String,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.AccessRights})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyName As String, rights As IEnumerable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule : string * seq&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; -&gt; Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" Usage="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule (keyName, rights)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="rights" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt;" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="f7212-102">承認規則のキー名。</span><span class="sxs-lookup"><span data-stu-id="f7212-102">The authorization rule key name.</span></span></param>
        <param name="rights"><span data-ttu-id="f7212-103">権限の一覧。</span><span class="sxs-lookup"><span data-stu-id="f7212-103">The list of rights.</span></span></param>
        <summary><span data-ttu-id="f7212-104"><see cref="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f7212-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAuthorizationRule (string keyName, string primaryKey, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; rights);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyName, string primaryKey, class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.ServiceBus.Messaging.AccessRights&gt; rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.#ctor(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.AccessRights})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyName As String, primaryKey As String, rights As IEnumerable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule : string * string * seq&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; -&gt; Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" Usage="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule (keyName, primaryKey, rights)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="primaryKey" Type="System.String" />
        <Parameter Name="rights" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt;" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="f7212-105">承認規則のキー名。</span><span class="sxs-lookup"><span data-stu-id="f7212-105">The authorization rule key name.</span></span></param>
        <param name="primaryKey"><span data-ttu-id="f7212-106">承認規則の主キー。</span><span class="sxs-lookup"><span data-stu-id="f7212-106">The primary key for the authorization rule.</span></span></param>
        <param name="rights"><span data-ttu-id="f7212-107">権限の一覧。</span><span class="sxs-lookup"><span data-stu-id="f7212-107">The list of rights.</span></span></param>
        <summary><span data-ttu-id="f7212-108"><see cref="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f7212-108">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAuthorizationRule (string keyName, string primaryKey, string secondaryKey, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; rights);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyName, string primaryKey, string secondaryKey, class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.ServiceBus.Messaging.AccessRights&gt; rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.#ctor(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.AccessRights})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyName As String, primaryKey As String, secondaryKey As String, rights As IEnumerable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule : string * string * string * seq&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; -&gt; Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" Usage="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule (keyName, primaryKey, secondaryKey, rights)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="primaryKey" Type="System.String" />
        <Parameter Name="secondaryKey" Type="System.String" />
        <Parameter Name="rights" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt;" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="f7212-109">承認規則のキー名。</span><span class="sxs-lookup"><span data-stu-id="f7212-109">The authorization rule key name.</span></span></param>
        <param name="primaryKey"><span data-ttu-id="f7212-110">承認規則の主キー。</span><span class="sxs-lookup"><span data-stu-id="f7212-110">The primary key for the authorization rule.</span></span></param>
        <param name="secondaryKey"><span data-ttu-id="f7212-111">承認規則のセカンダリ キー。</span><span class="sxs-lookup"><span data-stu-id="f7212-111">The secondary key for the authorization rule.</span></span></param>
        <param name="rights"><span data-ttu-id="f7212-112">権限の一覧。</span><span class="sxs-lookup"><span data-stu-id="f7212-112">The list of rights.</span></span></param>
        <summary><span data-ttu-id="f7212-113"><see cref="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f7212-113">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="sharedAccessAuthorizationRule.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="f7212-114">現在のオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7212-114">The object to compare with the current object.</span></span></param>
        <summary><span data-ttu-id="f7212-115">指定したオブジェクトが、現在のオブジェクトと等しいかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="f7212-115">Determines whether the specified object is equal to the current object.</span></span></summary>
        <returns><span data-ttu-id="f7212-116">指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="f7212-116">true if the specified object is equal to the current object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateRandomKey">
      <MemberSignature Language="C#" Value="public static string GenerateRandomKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateRandomKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.GenerateRandomKey" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateRandomKey () As String" />
      <MemberSignature Language="F#" Value="static member GenerateRandomKey : unit -&gt; string" Usage="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.GenerateRandomKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="f7212-117">承認規則のランダムなキーを生成します。</span><span class="sxs-lookup"><span data-stu-id="f7212-117">Generates the random key for the authorization rule.</span></span></summary>
        <returns><span data-ttu-id="f7212-118">承認規則のランダムなキーです。</span><span class="sxs-lookup"><span data-stu-id="f7212-118">The random key for the authorization rule.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="sharedAccessAuthorizationRule.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="f7212-119">このインスタンスのハッシュ コードを返します。</span><span class="sxs-lookup"><span data-stu-id="f7212-119">Returns the hash code for this instance.</span></span></summary>
        <returns><span data-ttu-id="f7212-120">対象のインスタンスのハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="f7212-120">The hash code for this instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public override sealed string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Overrides NotOverridable Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7212-121">取得または承認規則のキー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="f7212-121">Gets or sets the authorization rule key name.</span></span></summary>
        <value><span data-ttu-id="f7212-122">承認規則のキー名。</span><span class="sxs-lookup"><span data-stu-id="f7212-122">The authorization rule key name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidate">
      <MemberSignature Language="C#" Value="protected override void OnValidate ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.OnValidate" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidate ()" />
      <MemberSignature Language="F#" Value="override this.OnValidate : unit -&gt; unit" Usage="sharedAccessAuthorizationRule.OnValidate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="f7212-123">承認規則の有効性を確認します。</span><span class="sxs-lookup"><span data-stu-id="f7212-123">Checks the validity of the authorization rule.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryKey">
      <MemberSignature Language="C#" Value="public string PrimaryKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.PrimaryKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryKey As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.PrimaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7212-124">取得または承認規則の主キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="f7212-124">Gets or sets the primary key for the authorization rule.</span></span></summary>
        <value><span data-ttu-id="f7212-125">承認規則の主キー。</span><span class="sxs-lookup"><span data-stu-id="f7212-125">The primary key for the authorization rule.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryKey">
      <MemberSignature Language="C#" Value="public string SecondaryKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.SecondaryKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryKey As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.SecondaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7212-126">取得またはセカンダリ キーを承認規則を設定します。</span><span class="sxs-lookup"><span data-stu-id="f7212-126">Gets or sets the secondary key for the authorization rule.</span></span></summary>
        <value><span data-ttu-id="f7212-127">承認規則のセカンダリ キー。</span><span class="sxs-lookup"><span data-stu-id="f7212-127">The secondary key for the authorization rule.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serializer">
      <MemberSignature Language="C#" Value="public static readonly System.Runtime.Serialization.DataContractSerializer Serializer;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class System.Runtime.Serialization.DataContractSerializer Serializer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.Serializer" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Serializer As DataContractSerializer " />
      <MemberSignature Language="F#" Value=" staticval mutable Serializer : System.Runtime.Serialization.DataContractSerializer" Usage="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.Serializer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.DataContractSerializer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7212-128">SharedAccessAuthorizationRule 型のオブジェクトのシリアライザー。</span><span class="sxs-lookup"><span data-stu-id="f7212-128">A serializer for objects of type SharedAccessAuthorizationRule.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateRights">
      <MemberSignature Language="C#" Value="protected override void ValidateRights (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; value);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void ValidateRights(class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.ServiceBus.Messaging.AccessRights&gt; value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.ValidateRights(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.AccessRights})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub ValidateRights (value As IEnumerable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="override this.ValidateRights : seq&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; -&gt; unit" Usage="sharedAccessAuthorizationRule.ValidateRights value" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt;" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="f7212-129">確認へのアクセス権。</span><span class="sxs-lookup"><span data-stu-id="f7212-129">The access rights to check.</span></span></param>
        <summary><span data-ttu-id="f7212-130">指定したアクセス権の有効性を確認します。</span><span class="sxs-lookup"><span data-stu-id="f7212-130">Checks the validity of the specified access rights.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>