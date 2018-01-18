<Type Name="IscsiConnectionDetailsOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.IscsiConnectionDetailsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class IscsiConnectionDetailsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit IscsiConnectionDetailsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IscsiConnectionDetailsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module IscsiConnectionDetailsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type IscsiConnectionDetailsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="19037-101">これは、StorSimple のオブジェクトを管理する rest ベースの API</span><span class="sxs-lookup"><span data-stu-id="19037-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IscsiConnectionDetailsOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.IscsiConnectionDetailsOperationsExtensions.Get (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19037-102">Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="19037-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="19037-103">必須。</span><span class="sxs-lookup"><span data-stu-id="19037-103">Required.</span></span> <span data-ttu-id="19037-104">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="19037-104">The device id for which the call will be made.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="19037-105">必須。</span><span class="sxs-lookup"><span data-stu-id="19037-105">Required.</span></span> <span data-ttu-id="19037-106">カスタム要求ヘッダーをクライアントが使用できます。</span><span class="sxs-lookup"><span data-stu-id="19037-106">The Custom Request Headers which client can use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="19037-107">Iscsi 接続の詳細の一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="19037-107">The response model for the list of iscsi connection details.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IscsiConnectionDetailsOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.IscsiConnectionDetailsOperationsExtensions.GetAsync (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19037-108">Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="19037-108">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="19037-109">必須。</span><span class="sxs-lookup"><span data-stu-id="19037-109">Required.</span></span> <span data-ttu-id="19037-110">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="19037-110">The device id for which the call will be made.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="19037-111">必須。</span><span class="sxs-lookup"><span data-stu-id="19037-111">Required.</span></span> <span data-ttu-id="19037-112">カスタム要求ヘッダーをクライアントが使用できます。</span><span class="sxs-lookup"><span data-stu-id="19037-112">The Custom Request Headers which client can use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="19037-113">Iscsi 接続の詳細の一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="19037-113">The response model for the list of iscsi connection details.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>