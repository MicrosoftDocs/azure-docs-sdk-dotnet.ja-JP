<Type Name="DevicePublicKeyOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.DevicePublicKeyOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DevicePublicKeyOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DevicePublicKeyOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.DevicePublicKeyOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DevicePublicKeyOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DevicePublicKeyOperationsExtensions = class" />
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
            <span data-ttu-id="c4897-101">これは、StorSimple のオブジェクトを管理する rest ベースの API</span><span class="sxs-lookup"><span data-stu-id="c4897-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DevicePublicKeyOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DevicePublicKeyOperationsExtensions.Get (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c4897-102">Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c4897-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="c4897-103">必須。</span><span class="sxs-lookup"><span data-stu-id="c4897-103">Required.</span></span> <span data-ttu-id="c4897-104">デバイスの公開キーをフェッチお必要があります、デバイス Id</span><span class="sxs-lookup"><span data-stu-id="c4897-104">The Device Id for which we need to Fetch the Device Public Key</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c4897-105">必須。</span><span class="sxs-lookup"><span data-stu-id="c4897-105">Required.</span></span> <span data-ttu-id="c4897-106">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c4897-106">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="c4897-107">デバイスの公開キーの応答モデル。</span><span class="sxs-lookup"><span data-stu-id="c4897-107">The response model for Device PublicKey.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DevicePublicKeyOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DevicePublicKeyOperationsExtensions.GetAsync (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c4897-108">Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c4897-108">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="c4897-109">必須。</span><span class="sxs-lookup"><span data-stu-id="c4897-109">Required.</span></span> <span data-ttu-id="c4897-110">デバイスの公開キーをフェッチお必要があります、デバイス Id</span><span class="sxs-lookup"><span data-stu-id="c4897-110">The Device Id for which we need to Fetch the Device Public Key</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c4897-111">必須。</span><span class="sxs-lookup"><span data-stu-id="c4897-111">Required.</span></span> <span data-ttu-id="c4897-112">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c4897-112">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="c4897-113">デバイスの公開キーの応答モデル。</span><span class="sxs-lookup"><span data-stu-id="c4897-113">The response model for Device PublicKey.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>