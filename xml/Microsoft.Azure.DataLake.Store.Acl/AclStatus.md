<Type Name="AclStatus" FullName="Microsoft.Azure.DataLake.Store.Acl.AclStatus">
  <TypeSignature Language="C#" Value="public class AclStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AclStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.Acl.AclStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class AclStatus" />
  <TypeSignature Language="F#" Value="type AclStatus = class" />
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
    <summary>
            <span data-ttu-id="5332c-101">ID、8 進数のアクセス許可、および sticky ビット (ディレクトリ) の場合のみ、所有者 ID の Acl エントリをカプセル化するクラスをグループ化します。</span><span class="sxs-lookup"><span data-stu-id="5332c-101">Class that encapsulates Acl entries, owner ID, group ID, octal permission and sticky bit (only for a directory)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AclStatus (System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; list, string owner, string group, string permission, bool stickyBit);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; list, string owner, string group, string permission, bool stickyBit) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclStatus.#ctor(System.Collections.Generic.List{Microsoft.Azure.DataLake.Store.Acl.AclEntry},System.String,System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (list As List(Of AclEntry), owner As String, group As String, permission As String, stickyBit As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.DataLake.Store.Acl.AclStatus : System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; * string * string * string * bool -&gt; Microsoft.Azure.DataLake.Store.Acl.AclStatus" Usage="new Microsoft.Azure.DataLake.Store.Acl.AclStatus (list, owner, group, permission, stickyBit)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="list" Type="System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" />
        <Parameter Name="owner" Type="System.String" />
        <Parameter Name="group" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
        <Parameter Name="stickyBit" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="list"><span data-ttu-id="5332c-102">Acl エントリの一覧</span><span class="sxs-lookup"><span data-stu-id="5332c-102">Acl Entry list</span></span></param>
        <param name="owner"><span data-ttu-id="5332c-103">Owner</span><span class="sxs-lookup"><span data-stu-id="5332c-103">Owner</span></span></param>
        <param name="group"><span data-ttu-id="5332c-104">グループ Id</span><span class="sxs-lookup"><span data-stu-id="5332c-104">Group Id</span></span></param>
        <param name="permission"><span data-ttu-id="5332c-105">アクセス許可文字列</span><span class="sxs-lookup"><span data-stu-id="5332c-105">Permission string</span></span></param>
        <param name="stickyBit"><span data-ttu-id="5332c-106">Sticky ビット</span><span class="sxs-lookup"><span data-stu-id="5332c-106">Sticky Bit</span></span></param>
        <summary>
            <span data-ttu-id="5332c-107">Acl の状態を初期化します。</span><span class="sxs-lookup"><span data-stu-id="5332c-107">Initializes Acl Status</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Entries">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; Entries { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt; Entries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.Acl.AclStatus.Entries" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Entries As List(Of AclEntry)" />
      <MemberSignature Language="F#" Value="member this.Entries : System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;" Usage="Microsoft.Azure.DataLake.Store.Acl.AclStatus.Entries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.Acl.AclEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5332c-108">ファイルの ACL エントリ</span><span class="sxs-lookup"><span data-stu-id="5332c-108">ACL entries of the file</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Group">
      <MemberSignature Language="C#" Value="public string Group { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Group" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.Acl.AclStatus.Group" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Group As String" />
      <MemberSignature Language="F#" Value="member this.Group : string" Usage="Microsoft.Azure.DataLake.Store.Acl.AclStatus.Group" />
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
            <span data-ttu-id="5332c-109">ファイルを所有するグループ ID</span><span class="sxs-lookup"><span data-stu-id="5332c-109">Group ID that owns the file</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Owner">
      <MemberSignature Language="C#" Value="public string Owner { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Owner" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.Acl.AclStatus.Owner" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Owner As String" />
      <MemberSignature Language="F#" Value="member this.Owner : string" Usage="Microsoft.Azure.DataLake.Store.Acl.AclStatus.Owner" />
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
            <span data-ttu-id="5332c-110">ファイルの所有者</span><span class="sxs-lookup"><span data-stu-id="5332c-110">Owner of the file</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permission">
      <MemberSignature Language="C#" Value="public string Permission { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Permission" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.Acl.AclStatus.Permission" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Permission As String" />
      <MemberSignature Language="F#" Value="member this.Permission : string" Usage="Microsoft.Azure.DataLake.Store.Acl.AclStatus.Permission" />
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
            <span data-ttu-id="5332c-111">8 進数のアクセス許可</span><span class="sxs-lookup"><span data-stu-id="5332c-111">Octal permission</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StickyBit">
      <MemberSignature Language="C#" Value="public bool StickyBit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool StickyBit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.Acl.AclStatus.StickyBit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StickyBit As Boolean" />
      <MemberSignature Language="F#" Value="member this.StickyBit : bool" Usage="Microsoft.Azure.DataLake.Store.Acl.AclStatus.StickyBit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5332c-112">Sticky ビット</span><span class="sxs-lookup"><span data-stu-id="5332c-112">Sticky Bit</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>