<Type Name="AclEntry" FullName="Microsoft.Azure.DataLake.Store.Acl.AclEntry">
  <TypeSignature Language="C#" Value="public class AclEntry" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AclEntry extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.Acl.AclEntry" />
  <TypeSignature Language="VB.NET" Value="Public Class AclEntry" />
  <TypeSignature Language="F#" Value="type AclEntry = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AclEntry (Microsoft.Azure.DataLake.Store.Acl.AclType type, string userOrGroupId, Microsoft.Azure.DataLake.Store.Acl.AclScope scope, Microsoft.Azure.DataLake.Store.Acl.AclAction action);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.DataLake.Store.Acl.AclType type, string userOrGroupId, valuetype Microsoft.Azure.DataLake.Store.Acl.AclScope scope, valuetype Microsoft.Azure.DataLake.Store.Acl.AclAction action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclEntry.#ctor(Microsoft.Azure.DataLake.Store.Acl.AclType,System.String,Microsoft.Azure.DataLake.Store.Acl.AclScope,Microsoft.Azure.DataLake.Store.Acl.AclAction)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (type As AclType, userOrGroupId As String, scope As AclScope, action As AclAction)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.DataLake.Store.Acl.AclEntry : Microsoft.Azure.DataLake.Store.Acl.AclType * string * Microsoft.Azure.DataLake.Store.Acl.AclScope * Microsoft.Azure.DataLake.Store.Acl.AclAction -&gt; Microsoft.Azure.DataLake.Store.Acl.AclEntry" Usage="new Microsoft.Azure.DataLake.Store.Acl.AclEntry (type, userOrGroupId, scope, action)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="Microsoft.Azure.DataLake.Store.Acl.AclType" />
        <Parameter Name="userOrGroupId" Type="System.String" />
        <Parameter Name="scope" Type="Microsoft.Azure.DataLake.Store.Acl.AclScope" />
        <Parameter Name="action" Type="Microsoft.Azure.DataLake.Store.Acl.AclAction" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="6b03b-101">ACL エントリの種類: ユーザー/グループ/その他の/マスク</span><span class="sxs-lookup"><span data-stu-id="6b03b-101">Type of ACL entry: User/group/Other/mask</span></span></param>
        <param name="userOrGroupId"><span data-ttu-id="6b03b-102">ACL エントリの種類によって、オブジェクトのオブジェクト ID。</span><span class="sxs-lookup"><span data-stu-id="6b03b-102">Object ID of the object depending on the type of the ACL entry.</span></span> <span data-ttu-id="6b03b-103">その他の acl 型およびマスクのことが null</span><span class="sxs-lookup"><span data-stu-id="6b03b-103">For acl type other and mask it should be null</span></span></param>
        <param name="scope"><span data-ttu-id="6b03b-104">アクセスまたは既定値</span><span class="sxs-lookup"><span data-stu-id="6b03b-104">ACCESS or DEFAULT</span></span></param>
        <param name="action"><span data-ttu-id="6b03b-105">ACL を設定の種類</span><span class="sxs-lookup"><span data-stu-id="6b03b-105">The type of ACL to set</span></span></param>
        <summary>
            <span data-ttu-id="6b03b-106">パブリック コンストラクター</span><span class="sxs-lookup"><span data-stu-id="6b03b-106">Public constructor</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.DataLake.Store.Acl.AclAction Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.DataLake.Store.Acl.AclAction Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.Acl.AclEntry.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As AclAction" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.Azure.DataLake.Store.Acl.AclAction" Usage="Microsoft.Azure.DataLake.Store.Acl.AclEntry.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.Acl.AclAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6b03b-107">ACL を設定の種類</span><span class="sxs-lookup"><span data-stu-id="6b03b-107">The type of ACL to set</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.DataLake.Store.Acl.AclEntry entry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Equals(class Microsoft.Azure.DataLake.Store.Acl.AclEntry entry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclEntry.Equals(Microsoft.Azure.DataLake.Store.Acl.AclEntry)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (entry As AclEntry) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.DataLake.Store.Acl.AclEntry -&gt; bool" Usage="aclEntry.Equals entry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entry" Type="Microsoft.Azure.DataLake.Store.Acl.AclEntry" />
      </Parameters>
      <Docs>
        <param name="entry"><span data-ttu-id="6b03b-108">Acl エントリ</span><span class="sxs-lookup"><span data-stu-id="6b03b-108">Acl entry</span></span></param>
        <summary>
            <span data-ttu-id="6b03b-109">型、型名、スコープ、アクションはすべて同じ場合、true を返します</span><span class="sxs-lookup"><span data-stu-id="6b03b-109">Returns true if the type, type name, scope and action are all same</span></span>
            </summary>
        <returns><span data-ttu-id="6b03b-110">Acl エントリが偽と等しい場合は true</span><span class="sxs-lookup"><span data-stu-id="6b03b-110">True if Acl entries are equal else false</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclEntry.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="aclEntry.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="6b03b-111">Acl エントリ</span><span class="sxs-lookup"><span data-stu-id="6b03b-111">Acl entry</span></span></param>
        <summary>
            <span data-ttu-id="6b03b-112">型、型名、スコープ、アクションはすべて同じ場合、true を返します</span><span class="sxs-lookup"><span data-stu-id="6b03b-112">Returns true if the type, type name, scope and action are all same</span></span>
            </summary>
        <returns><span data-ttu-id="6b03b-113">AclEntries が同じ他 false の場合は true</span><span class="sxs-lookup"><span data-stu-id="6b03b-113">true if AclEntries are same else false</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseAclEntriesString">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; ParseAclEntriesString (string aclEntries);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; ParseAclEntriesString(string aclEntries) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclEntry.ParseAclEntriesString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ParseAclEntriesString (aclEntries As String) As List(Of AclEntry)" />
      <MemberSignature Language="F#" Value="static member ParseAclEntriesString : string -&gt; System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" Usage="Microsoft.Azure.DataLake.Store.Acl.AclEntry.ParseAclEntriesString aclEntries" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="aclEntries" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="aclEntries"><span data-ttu-id="6b03b-114">各エントリで区切られた acl エントリを含む文字列 ','</span><span class="sxs-lookup"><span data-stu-id="6b03b-114">String containing the acl entries each entry is delimited by ','</span></span></param>
        <summary>
            <span data-ttu-id="6b03b-115">各 acl エントリの文字列を解析し、すべての acl エントリの一覧を返します</span><span class="sxs-lookup"><span data-stu-id="6b03b-115">Parses each acl entry string and then returns the list of all acl entries</span></span>
            </summary>
        <returns><span data-ttu-id="6b03b-116">Acl エントリの一覧</span><span class="sxs-lookup"><span data-stu-id="6b03b-116">List of acl entries</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseAclEntryString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.DataLake.Store.Acl.AclEntry ParseAclEntryString (string aclEntry, bool removeAcl);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.DataLake.Store.Acl.AclEntry ParseAclEntryString(string aclEntry, bool removeAcl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclEntry.ParseAclEntryString(System.String,System.Boolean)" />
      <MemberSignature Language="F#" Value="static member ParseAclEntryString : string * bool -&gt; Microsoft.Azure.DataLake.Store.Acl.AclEntry" Usage="Microsoft.Azure.DataLake.Store.Acl.AclEntry.ParseAclEntryString (aclEntry, removeAcl)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.Acl.AclEntry</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="aclEntry" Type="System.String" />
        <Parameter Name="removeAcl" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="aclEntry"><span data-ttu-id="6b03b-117">Acl エントリの文字列で区切られた ':'</span><span class="sxs-lookup"><span data-stu-id="6b03b-117">Acl Entry string delimited by ':'</span></span></param>
        <param name="removeAcl"><span data-ttu-id="6b03b-118">この文字列が Acl を削除するかどうか。</span><span class="sxs-lookup"><span data-stu-id="6b03b-118">Whether this string is for removing Acl.</span></span></param>
        <summary>
            <span data-ttu-id="6b03b-119">Acl の種類、acl の種類 Id、acl のスコープおよび acl のアクション (アクセス許可) に AclEntry 文字列を解析します。</span><span class="sxs-lookup"><span data-stu-id="6b03b-119">Parses a AclEntry string into acl type, acl type Id, acl scope and acl action (permissions).</span></span>
            <span data-ttu-id="6b03b-120">Acl の文字列が正しくない場合は、例外をスローします。</span><span class="sxs-lookup"><span data-stu-id="6b03b-120">Throws exception if the acl string is not correct.</span></span>
            </summary>
        <returns><span data-ttu-id="6b03b-121">Acl エントリ インスタンス</span><span class="sxs-lookup"><span data-stu-id="6b03b-121">Acl Entry instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.DataLake.Store.Acl.AclScope Scope { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.DataLake.Store.Acl.AclScope Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.Acl.AclEntry.Scope" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Scope As AclScope" />
      <MemberSignature Language="F#" Value="member this.Scope : Microsoft.Azure.DataLake.Store.Acl.AclScope" Usage="Microsoft.Azure.DataLake.Store.Acl.AclEntry.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.Acl.AclScope</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6b03b-122">アクセスまたは既定値</span><span class="sxs-lookup"><span data-stu-id="6b03b-122">ACCESS or DEFAULT</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializeAcl">
      <MemberSignature Language="C#" Value="public static string SerializeAcl (System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclList, bool removeAcl);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string SerializeAcl(class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; aclList, bool removeAcl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclEntry.SerializeAcl(System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SerializeAcl (aclList As List(Of AclEntry), removeAcl As Boolean) As String" />
      <MemberSignature Language="F#" Value="static member SerializeAcl : System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * bool -&gt; string" Usage="Microsoft.Azure.DataLake.Store.Acl.AclEntry.SerializeAcl (aclList, removeAcl)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="aclList" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="removeAcl" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="aclList"><span data-ttu-id="6b03b-123">ACL エントリの一覧</span><span class="sxs-lookup"><span data-stu-id="6b03b-123">List of ACL entries</span></span></param>
        <param name="removeAcl"><span data-ttu-id="6b03b-124">Acl を削除中に呼び出された場合は true。</span><span class="sxs-lookup"><span data-stu-id="6b03b-124">True if is called while removing ACLs</span></span></param>
        <summary>
            <span data-ttu-id="6b03b-125">ACL エントリの一覧から ACL エントリを文字列形式にシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="6b03b-125">Serializes the ACL entries from a list of ACL entries to a string format</span></span>
            </summary>
        <returns><span data-ttu-id="6b03b-126">各エントリで区切られた文字列の形式で連結する Acl エントリの一覧 ','</span><span class="sxs-lookup"><span data-stu-id="6b03b-126">List of Acl entries concatenated in a string format each entry is delimited by ','</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclEntry.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="aclEntry.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public string ToString (bool removeAcl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string ToString(bool removeAcl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclEntry.ToString(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToString (removeAcl As Boolean) As String" />
      <MemberSignature Language="F#" Value="override this.ToString : bool -&gt; string" Usage="aclEntry.ToString removeAcl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="removeAcl" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="removeAcl"><span data-ttu-id="6b03b-127">Acl を削除中に呼び出された場合は true。</span><span class="sxs-lookup"><span data-stu-id="6b03b-127">True if is called while removing ACLs</span></span></param>
        <summary>
            <span data-ttu-id="6b03b-128">各 ACL エントリの文字列形式を返します</span><span class="sxs-lookup"><span data-stu-id="6b03b-128">Returns the string format of each ACL entry</span></span>
            </summary>
        <returns><span data-ttu-id="6b03b-129">各部分がで区切られた文字列の形式で Acl エントリ ':'</span><span class="sxs-lookup"><span data-stu-id="6b03b-129">Acl entry in a string format where each part is delimited by ':'</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.DataLake.Store.Acl.AclType Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.DataLake.Store.Acl.AclType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.Acl.AclEntry.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As AclType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.DataLake.Store.Acl.AclType" Usage="Microsoft.Azure.DataLake.Store.Acl.AclEntry.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.Acl.AclType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6b03b-130">ACL エントリの種類: ユーザー/グループ/その他の/マスク</span><span class="sxs-lookup"><span data-stu-id="6b03b-130">Type of ACL entry: User/group/Other/mask</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserOrGroupId">
      <MemberSignature Language="C#" Value="public string UserOrGroupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserOrGroupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.Acl.AclEntry.UserOrGroupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserOrGroupId As String" />
      <MemberSignature Language="F#" Value="member this.UserOrGroupId : string" Usage="Microsoft.Azure.DataLake.Store.Acl.AclEntry.UserOrGroupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6b03b-131">ACL エントリの種類に応じてオブジェクトのオブジェクト ID</span><span class="sxs-lookup"><span data-stu-id="6b03b-131">Object ID of the object depending on the type of the ACL entry</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>