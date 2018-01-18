<Type Name="RepairTaskState" FullName="System.Fabric.Repair.RepairTaskState">
  <TypeSignature Language="C#" Value="public enum RepairTaskState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RepairTaskState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.RepairTaskState" />
  <TypeSignature Language="VB.NET" Value="Public Enum RepairTaskState" />
  <TypeSignature Language="F#" Value="type RepairTaskState = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="f526c-101">修復タスクのワークフローの状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="f526c-101">Specifies the workflow state of a repair task.</span></span></para>
      <para><span data-ttu-id="f526c-102">この型は、Service Fabric プラットフォームをサポートしています。コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="f526c-102">This type supports the Service Fabric platform; it is not meant to be used directly from your code.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Approved">
      <MemberSignature Language="C#" Value="Approved" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskState Approved = int32(8)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskState.Approved" />
      <MemberSignature Language="VB.NET" Value="Approved" />
      <MemberSignature Language="F#" Value="Approved = 8" Usage="System.Fabric.Repair.RepairTaskState.Approved" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskState</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f526c-103">修復タスクを実行しても安全ですが修復マネージャーが承認されることを示します。</span><span class="sxs-lookup"><span data-stu-id="f526c-103">Indicates that the repair task has been approved by the Repair Manager and is safe to execute.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Claimed">
      <MemberSignature Language="C#" Value="Claimed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskState Claimed = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskState.Claimed" />
      <MemberSignature Language="VB.NET" Value="Claimed" />
      <MemberSignature Language="F#" Value="Claimed = 2" Usage="System.Fabric.Repair.RepairTaskState.Claimed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f526c-104">修復タスクが修復 executor により要求されてことを示します。</span><span class="sxs-lookup"><span data-stu-id="f526c-104">Indicates that the repair task has been claimed by a repair executor.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskState Completed = int32(64)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskState.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 64" Usage="System.Fabric.Repair.RepairTaskState.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskState</ReturnType>
      </ReturnValue>
      <MemberValue>64</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f526c-105">修復タスクが完了したら、それ以上の状態の変更は行われませんことを示します。</span><span class="sxs-lookup"><span data-stu-id="f526c-105">Indicates that the repair task has completed, and no further state changes will occur.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Created">
      <MemberSignature Language="C#" Value="Created" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskState Created = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskState.Created" />
      <MemberSignature Language="VB.NET" Value="Created" />
      <MemberSignature Language="F#" Value="Created = 1" Usage="System.Fabric.Repair.RepairTaskState.Created" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f526c-106">修復タスクが作成されていることを示します。</span><span class="sxs-lookup"><span data-stu-id="f526c-106">Indicates that the repair task has been created.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Executing">
      <MemberSignature Language="C#" Value="Executing" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskState Executing = int32(16)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskState.Executing" />
      <MemberSignature Language="VB.NET" Value="Executing" />
      <MemberSignature Language="F#" Value="Executing = 16" Usage="System.Fabric.Repair.RepairTaskState.Executing" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskState</ReturnType>
      </ReturnValue>
      <MemberValue>16</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f526c-107">修復タスクの実行が進行中であることを示します。</span><span class="sxs-lookup"><span data-stu-id="f526c-107">Indicates that execution of the repair task is in progress.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskState Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskState.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Repair.RepairTaskState.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f526c-108">修復タスクの状態が無効であることを示します。</span><span class="sxs-lookup"><span data-stu-id="f526c-108">Indicates that the repair task state is invalid.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Preparing">
      <MemberSignature Language="C#" Value="Preparing" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskState Preparing = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskState.Preparing" />
      <MemberSignature Language="VB.NET" Value="Preparing" />
      <MemberSignature Language="F#" Value="Preparing = 4" Usage="System.Fabric.Repair.RepairTaskState.Preparing" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f526c-109">修復マネージャーがリソースをオフラインにする適切にして、通常、修復作業の影響を処理するシステムを準備することを示します。</span><span class="sxs-lookup"><span data-stu-id="f526c-109">Indicates that the Repair Manager is preparing the system to handle the impact of the repair task, usually by taking resources offline gracefully.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Restoring">
      <MemberSignature Language="C#" Value="Restoring" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskState Restoring = int32(32)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskState.Restoring" />
      <MemberSignature Language="VB.NET" Value="Restoring" />
      <MemberSignature Language="F#" Value="Restoring = 32" Usage="System.Fabric.Repair.RepairTaskState.Restoring" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskState</ReturnType>
      </ReturnValue>
      <MemberValue>32</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f526c-110">Manager を修復は、システムの復元の前に修復状態に通常リソースをオンラインに戻すを戻すことによってを示します。</span><span class="sxs-lookup"><span data-stu-id="f526c-110">Indicates that the Repair Manager is restoring the system to its pre-repair state, usually by bringing resources back online.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>