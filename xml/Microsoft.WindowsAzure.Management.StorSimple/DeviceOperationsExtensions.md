<Type Name="DeviceOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.DeviceOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeviceOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeviceOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.DeviceOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeviceOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeviceOperationsExtensions = class" />
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
            <span data-ttu-id="2f70b-101">これは、StorSimple のオブジェクトを管理する rest ベースの API</span><span class="sxs-lookup"><span data-stu-id="2f70b-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceListResponse List (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceListResponse List(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceOperationsExtensions.List(Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceListResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceOperationsExtensions.List (operations, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations" RefType="this" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f70b-102">Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="2f70b-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="2f70b-103">必須。</span><span class="sxs-lookup"><span data-stu-id="2f70b-103">Required.</span></span> <span data-ttu-id="2f70b-104">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2f70b-104">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="2f70b-105">デバイスの一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="2f70b-105">The response model for the list of devices.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceListResponse&gt; ListAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceListResponse&gt; ListAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceOperationsExtensions.ListAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceListResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceOperationsExtensions.ListAsync (operations, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations" RefType="this" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f70b-106">Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="2f70b-106">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="2f70b-107">必須。</span><span class="sxs-lookup"><span data-stu-id="2f70b-107">Required.</span></span> <span data-ttu-id="2f70b-108">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2f70b-108">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="2f70b-109">デバイスの一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="2f70b-109">The response model for the list of devices.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>