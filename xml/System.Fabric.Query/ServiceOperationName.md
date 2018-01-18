<Type Name="ServiceOperationName" FullName="System.Fabric.Query.ServiceOperationName">
  <TypeSignature Language="C#" Value="public enum ServiceOperationName" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServiceOperationName extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ServiceOperationName" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServiceOperationName" />
  <TypeSignature Language="F#" Value="type ServiceOperationName = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="e38da-101">ステートフル サービス レプリカまたはステートレス サービス インスタンスを呼び出すことによって取得の現在のアクティブなライフ サイクル操作の指定<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />です。</span><span class="sxs-lookup"><span data-stu-id="e38da-101">Specifies the current active life-cycle operation on a stateful service replica or stateless service instance retrieved by calling <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="Abort" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceOperationName Abort = int32(16)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceOperationName.Abort" />
      <MemberSignature Language="VB.NET" Value="Abort" />
      <MemberSignature Language="F#" Value="Abort = 16" Usage="System.Fabric.Query.ServiceOperationName.Abort" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>16</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e38da-102">サービス レプリカまたはインスタンスを中止しています。</span><span class="sxs-lookup"><span data-stu-id="e38da-102">The service replica or instance is being aborted.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ChangeRole">
      <MemberSignature Language="C#" Value="ChangeRole" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceOperationName ChangeRole = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceOperationName.ChangeRole" />
      <MemberSignature Language="VB.NET" Value="ChangeRole" />
      <MemberSignature Language="F#" Value="ChangeRole = 4" Usage="System.Fabric.Query.ServiceOperationName.ChangeRole" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e38da-103">サービスのレプリカでは、ロールを変更します。</span><span class="sxs-lookup"><span data-stu-id="e38da-103">The service replica is changing roles.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Close">
      <MemberSignature Language="C#" Value="Close" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceOperationName Close = int32(8)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceOperationName.Close" />
      <MemberSignature Language="VB.NET" Value="Close" />
      <MemberSignature Language="F#" Value="Close = 8" Usage="System.Fabric.Query.ServiceOperationName.Close" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e38da-104">サービス レプリカまたはインスタンスを閉じています。</span><span class="sxs-lookup"><span data-stu-id="e38da-104">The service replica or instance is being closed.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceOperationName Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceOperationName.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Query.ServiceOperationName.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e38da-105">将来使用するために予約されています。</span><span class="sxs-lookup"><span data-stu-id="e38da-105">Reserved for future use.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceOperationName None = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceOperationName.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 1" Usage="System.Fabric.Query.ServiceOperationName.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e38da-106">サービス レプリカまたはインスタンスは、任意のライフ サイクルの変化を予定はありません。</span><span class="sxs-lookup"><span data-stu-id="e38da-106">The service replica or instance is not going through any life-cycle changes.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="Open" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceOperationName Open = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceOperationName.Open" />
      <MemberSignature Language="VB.NET" Value="Open" />
      <MemberSignature Language="F#" Value="Open = 2" Usage="System.Fabric.Query.ServiceOperationName.Open" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e38da-107">サービス レプリカまたはインスタンスを開いています。</span><span class="sxs-lookup"><span data-stu-id="e38da-107">The service replica or instance is being opened.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>