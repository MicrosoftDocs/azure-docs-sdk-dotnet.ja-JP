<Type Name="ComposeDeploymentStatus" FullName="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus">
  <TypeSignature Language="C#" Value="public enum ComposeDeploymentStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComposeDeploymentStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum ComposeDeploymentStatus" />
  <TypeSignature Language="F#" Value="type ComposeDeploymentStatus = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="e0a0a-101">作成する展開のステータスを指定します。</span><span class="sxs-lookup"><span data-stu-id="e0a0a-101">Specifies the status of the compose deployment.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Creating">
      <MemberSignature Language="C#" Value="Creating" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus Creating = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus.Creating" />
      <MemberSignature Language="VB.NET" Value="Creating" />
      <MemberSignature Language="F#" Value="Creating = 2" Usage="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus.Creating" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0a0a-102">バック グラウンドでは、アプリケーションを作成しています。</span><span class="sxs-lookup"><span data-stu-id="e0a0a-102">The application is being created at background.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Deleting">
      <MemberSignature Language="C#" Value="Deleting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus Deleting = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus.Deleting" />
      <MemberSignature Language="VB.NET" Value="Deleting" />
      <MemberSignature Language="F#" Value="Deleting = 4" Usage="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus.Deleting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0a0a-103">バック グラウンドでは、アプリケーションを削除しています。</span><span class="sxs-lookup"><span data-stu-id="e0a0a-103">The application is being deleted at background.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Failed">
      <MemberSignature Language="C#" Value="Failed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus Failed = int32(6)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus.Failed" />
      <MemberSignature Language="VB.NET" Value="Failed" />
      <MemberSignature Language="F#" Value="Failed = 6" Usage="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus.Failed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0a0a-104">作成または削除は永続的な失敗したため終了しました。</span><span class="sxs-lookup"><span data-stu-id="e0a0a-104">Creation or deletion was terminated due to persistent failures.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0a0a-105">無効。</span><span class="sxs-lookup"><span data-stu-id="e0a0a-105">Invalid.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Provisioning">
      <MemberSignature Language="C#" Value="Provisioning" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus Provisioning = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus.Provisioning" />
      <MemberSignature Language="VB.NET" Value="Provisioning" />
      <MemberSignature Language="F#" Value="Provisioning = 1" Usage="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus.Provisioning" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0a0a-106">アプリケーションの種類は、バック グラウンドでプロビジョニング中です。</span><span class="sxs-lookup"><span data-stu-id="e0a0a-106">The application type is being provisioned at background.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Ready">
      <MemberSignature Language="C#" Value="Ready" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus Ready = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus.Ready" />
      <MemberSignature Language="VB.NET" Value="Ready" />
      <MemberSignature Language="F#" Value="Ready = 3" Usage="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus.Ready" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0a0a-107">Docker は、展開の作成を作成またはアップグレードが完了しました。</span><span class="sxs-lookup"><span data-stu-id="e0a0a-107">The docker compose deployment creation or upgrade is complete.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unprovisioning">
      <MemberSignature Language="C#" Value="Unprovisioning" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus Unprovisioning = int32(5)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus.Unprovisioning" />
      <MemberSignature Language="VB.NET" Value="Unprovisioning" />
      <MemberSignature Language="F#" Value="Unprovisioning = 5" Usage="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus.Unprovisioning" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0a0a-108">アプリケーションの種類はバック グラウンドで準備を解除されています。</span><span class="sxs-lookup"><span data-stu-id="e0a0a-108">The application type is being unprovisioned at background.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Upgrading">
      <MemberSignature Language="C#" Value="Upgrading" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus Upgrading = int32(7)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus.Upgrading" />
      <MemberSignature Language="VB.NET" Value="Upgrading" />
      <MemberSignature Language="F#" Value="Upgrading = 7" Usage="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus.Upgrading" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus</ReturnType>
      </ReturnValue>
      <MemberValue>7</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0a0a-109">展開をアップグレード中です。</span><span class="sxs-lookup"><span data-stu-id="e0a0a-109">The deployment is being upgraded.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>