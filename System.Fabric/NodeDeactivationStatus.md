<Type Name="NodeDeactivationStatus" FullName="System.Fabric.NodeDeactivationStatus">
  <TypeSignature Language="C#" Value="public enum NodeDeactivationStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed NodeDeactivationStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NodeDeactivationStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum NodeDeactivationStatus" />
  <TypeSignature Language="F#" Value="type NodeDeactivationStatus = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="de566-101">ノード非アクティブ化タスクの状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="de566-101">Specified the status for a node deactivation task.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationStatus Completed = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationStatus.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 3" Usage="System.Fabric.NodeDeactivationStatus.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="de566-102">タスクが完了したとします。</span><span class="sxs-lookup"><span data-stu-id="de566-102">The task is completed.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationStatus None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationStatus.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="System.Fabric.NodeDeactivationStatus.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="de566-103">状態は、タスクに関連付けではありません。</span><span class="sxs-lookup"><span data-stu-id="de566-103">No status is associated with the task.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="SafetyCheckComplete">
      <MemberSignature Language="C#" Value="SafetyCheckComplete" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationStatus SafetyCheckComplete = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationStatus.SafetyCheckComplete" />
      <MemberSignature Language="VB.NET" Value="SafetyCheckComplete" />
      <MemberSignature Language="F#" Value="SafetyCheckComplete = 2" Usage="System.Fabric.NodeDeactivationStatus.SafetyCheckComplete" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="de566-104">タスクのすべての安全性チェックが完了します。</span><span class="sxs-lookup"><span data-stu-id="de566-104">All the safety checks have been completed for the task.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="SafetyCheckInProgress">
      <MemberSignature Language="C#" Value="SafetyCheckInProgress" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationStatus SafetyCheckInProgress = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationStatus.SafetyCheckInProgress" />
      <MemberSignature Language="VB.NET" Value="SafetyCheckInProgress" />
      <MemberSignature Language="F#" Value="SafetyCheckInProgress = 1" Usage="System.Fabric.NodeDeactivationStatus.SafetyCheckInProgress" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="de566-105">タスクの進行中の安全性チェックします。</span><span class="sxs-lookup"><span data-stu-id="de566-105">Safety checks are in progress for the task.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>