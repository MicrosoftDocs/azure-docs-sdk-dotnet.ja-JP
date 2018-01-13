<Type Name="LeaseState" FullName="Microsoft.WindowsAzure.Storage.Blob.LeaseState">
  <TypeSignature Language="C#" Value="public enum LeaseState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed LeaseState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.LeaseState" />
  <TypeSignature Language="VB.NET" Value="Public Enum LeaseState" />
  <TypeSignature Language="F#" Value="type LeaseState = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="92dd8-101">リソースのリース状態です。</span><span class="sxs-lookup"><span data-stu-id="92dd8-101">The lease state of a resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Available">
      <MemberSignature Language="C#" Value="Available" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseState Available = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.LeaseState.Available" />
      <MemberSignature Language="VB.NET" Value="Available" />
      <MemberSignature Language="F#" Value="Available = 1" Usage="Microsoft.WindowsAzure.Storage.Blob.LeaseState.Available" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="92dd8-102">リースが利用可能な状態です。</span><span class="sxs-lookup"><span data-stu-id="92dd8-102">The lease is in the Available state.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Breaking">
      <MemberSignature Language="C#" Value="Breaking" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseState Breaking = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.LeaseState.Breaking" />
      <MemberSignature Language="VB.NET" Value="Breaking" />
      <MemberSignature Language="F#" Value="Breaking = 4" Usage="Microsoft.WindowsAzure.Storage.Blob.LeaseState.Breaking" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="92dd8-103">リースは重大な状態です。</span><span class="sxs-lookup"><span data-stu-id="92dd8-103">The lease is in the Breaking state.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Broken">
      <MemberSignature Language="C#" Value="Broken" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseState Broken = int32(5)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.LeaseState.Broken" />
      <MemberSignature Language="VB.NET" Value="Broken" />
      <MemberSignature Language="F#" Value="Broken = 5" Usage="Microsoft.WindowsAzure.Storage.Blob.LeaseState.Broken" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseState</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="92dd8-104">リースは中断状態です。</span><span class="sxs-lookup"><span data-stu-id="92dd8-104">The lease is in the Broken state.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Expired">
      <MemberSignature Language="C#" Value="Expired" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseState Expired = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.LeaseState.Expired" />
      <MemberSignature Language="VB.NET" Value="Expired" />
      <MemberSignature Language="F#" Value="Expired = 3" Usage="Microsoft.WindowsAzure.Storage.Blob.LeaseState.Expired" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="92dd8-105">リースが期限切れ状態です。</span><span class="sxs-lookup"><span data-stu-id="92dd8-105">The lease is in the Expired state.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Leased">
      <MemberSignature Language="C#" Value="Leased" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseState Leased = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.LeaseState.Leased" />
      <MemberSignature Language="VB.NET" Value="Leased" />
      <MemberSignature Language="F#" Value="Leased = 2" Usage="Microsoft.WindowsAzure.Storage.Blob.LeaseState.Leased" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="92dd8-106">リースでは、状態は Leased です。</span><span class="sxs-lookup"><span data-stu-id="92dd8-106">The lease is in the Leased state.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unspecified">
      <MemberSignature Language="C#" Value="Unspecified" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseState Unspecified = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.LeaseState.Unspecified" />
      <MemberSignature Language="VB.NET" Value="Unspecified" />
      <MemberSignature Language="F#" Value="Unspecified = 0" Usage="Microsoft.WindowsAzure.Storage.Blob.LeaseState.Unspecified" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="92dd8-107">リースの状態が指定されていません。</span><span class="sxs-lookup"><span data-stu-id="92dd8-107">The lease state is not specified.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>