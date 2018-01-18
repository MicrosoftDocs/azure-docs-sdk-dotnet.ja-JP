<Type Name="SharedAccessQueuePolicy" FullName="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy">
  <TypeSignature Language="C#" Value="public sealed class SharedAccessQueuePolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedAccessQueuePolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedAccessQueuePolicy" />
  <TypeSignature Language="F#" Value="type SharedAccessQueuePolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a9ac8-101">開始時刻、有効期限、および共有アクセス署名のアクセス許可を指定する、キューの共有アクセス ポリシーを表します。</span><span class="sxs-lookup"><span data-stu-id="a9ac8-101">Represents a shared access policy for a queue, which specifies the start time, expiry time, and permissions for a shared access signature.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessQueuePolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a9ac8-102">SharedAccessQueuePolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a9ac8-102">Initializes a new instance of the SharedAccessQueuePolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permissions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions Permissions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions Permissions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy.Permissions" />
      <MemberSignature Language="VB.NET" Value="Public Property Permissions As SharedAccessQueuePermissions" />
      <MemberSignature Language="F#" Value="member this.Permissions : Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy.Permissions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9ac8-103">取得または、この共有アクセス ポリシーに関連付けられている共有アクセス署名のアクセス許可を設定します。</span><span class="sxs-lookup"><span data-stu-id="a9ac8-103">Gets or sets the permissions for a shared access signature associated with this shared access policy.</span></span>
            </summary>
        <value><span data-ttu-id="a9ac8-104"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a9ac8-104">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionsFromString">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions PermissionsFromString (string input);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions PermissionsFromString(string input) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy.PermissionsFromString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PermissionsFromString (input As String) As SharedAccessQueuePermissions" />
      <MemberSignature Language="F#" Value="static member PermissionsFromString : string -&gt; Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions" Usage="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy.PermissionsFromString input" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="input" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="input"><span data-ttu-id="a9ac8-105">文字列の形式で共有アクセス許可。</span><span class="sxs-lookup"><span data-stu-id="a9ac8-105">The shared access permissions in string format.</span></span></param>
        <summary>
            <span data-ttu-id="a9ac8-106">構築、<see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions" />アクセス許可文字列からオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a9ac8-106">Constructs a <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions" /> object from a permissions string.</span></span>
            </summary>
        <returns><span data-ttu-id="a9ac8-107"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a9ac8-107">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionsToString">
      <MemberSignature Language="C#" Value="public static string PermissionsToString (Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string PermissionsToString(valuetype Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy.PermissionsToString(Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PermissionsToString (permissions As SharedAccessQueuePermissions) As String" />
      <MemberSignature Language="F#" Value="static member PermissionsToString : Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy.PermissionsToString permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="a9ac8-108"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a9ac8-108">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePermissions" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="a9ac8-109">文字列に、共有アクセス ポリシーの指定されたアクセス許可に変換します。</span><span class="sxs-lookup"><span data-stu-id="a9ac8-109">Converts the permissions specified for the shared access policy to a string.</span></span>
            </summary>
        <returns><span data-ttu-id="a9ac8-110">文字列の形式で共有アクセス許可。</span><span class="sxs-lookup"><span data-stu-id="a9ac8-110">The shared access permissions in string format.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessExpiryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SharedAccessExpiryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SharedAccessExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy.SharedAccessExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessExpiryTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SharedAccessExpiryTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy.SharedAccessExpiryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9ac8-111">取得または、この共有アクセス ポリシーに関連付けられている共有アクセス署名の有効期限を設定します。</span><span class="sxs-lookup"><span data-stu-id="a9ac8-111">Gets or sets the expiry time for a shared access signature associated with this shared access policy.</span></span>
            </summary>
        <value><span data-ttu-id="a9ac8-112">A<see cref="T:System.DateTimeOffset" />共有アクセスの有効期限を指定します。</span><span class="sxs-lookup"><span data-stu-id="a9ac8-112">A <see cref="T:System.DateTimeOffset" /> specifying the shared access expiry time.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SharedAccessStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SharedAccessStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy.SharedAccessStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessStartTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SharedAccessStartTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy.SharedAccessStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9ac8-113">取得または、この共有アクセス ポリシーに関連付けられている共有アクセス署名の開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="a9ac8-113">Gets or sets the start time for a shared access signature associated with this shared access policy.</span></span>
            </summary>
        <value><span data-ttu-id="a9ac8-114">A<see cref="T:System.DateTimeOffset" />開始時刻を共有のアクセスを指定します。</span><span class="sxs-lookup"><span data-stu-id="a9ac8-114">A <see cref="T:System.DateTimeOffset" /> specifying the shared access start time.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>