<Type Name="JobStatus" FullName="Microsoft.Azure.Devices.JobStatus">
  <TypeSignature Language="C#" Value="public enum JobStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed JobStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.JobStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum JobStatus" />
  <TypeSignature Language="F#" Value="type JobStatus = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f73a3-101">ジョブのさまざまなジョブの状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="f73a3-101">Specifies the various job status for a job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Cancelled">
      <MemberSignature Language="C#" Value="Cancelled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.JobStatus Cancelled = int32(5)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.JobStatus.Cancelled" />
      <MemberSignature Language="VB.NET" Value="Cancelled" />
      <MemberSignature Language="F#" Value="Cancelled = 5" Usage="Microsoft.Azure.Devices.JobStatus.Cancelled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="cancelled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobStatus</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f73a3-102">ジョブの実行が取り消されましたことを示します</span><span class="sxs-lookup"><span data-stu-id="f73a3-102">Indicates that a Job execution was cancelled</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.JobStatus Completed = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.JobStatus.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 3" Usage="Microsoft.Azure.Devices.JobStatus.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="completed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f73a3-103">ジョブの実行が完了したことを示します</span><span class="sxs-lookup"><span data-stu-id="f73a3-103">Indicates that a Job execution is completed</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Enqueued">
      <MemberSignature Language="C#" Value="Enqueued" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.JobStatus Enqueued = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.JobStatus.Enqueued" />
      <MemberSignature Language="VB.NET" Value="Enqueued" />
      <MemberSignature Language="F#" Value="Enqueued = 1" Usage="Microsoft.Azure.Devices.JobStatus.Enqueued" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="enqueued")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f73a3-104">ジョブが実行するためのキューであることを示します</span><span class="sxs-lookup"><span data-stu-id="f73a3-104">Indicates that a Job is in the queue for execution</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Failed">
      <MemberSignature Language="C#" Value="Failed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.JobStatus Failed = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.JobStatus.Failed" />
      <MemberSignature Language="VB.NET" Value="Failed" />
      <MemberSignature Language="F#" Value="Failed = 4" Usage="Microsoft.Azure.Devices.JobStatus.Failed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="failed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobStatus</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f73a3-105">ジョブの実行が失敗したことを示します</span><span class="sxs-lookup"><span data-stu-id="f73a3-105">Indicates that a Job execution failed</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Queued">
      <MemberSignature Language="C#" Value="Queued" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.JobStatus Queued = int32(7)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.JobStatus.Queued" />
      <MemberSignature Language="VB.NET" Value="Queued" />
      <MemberSignature Language="F#" Value="Queued = 7" Usage="Microsoft.Azure.Devices.JobStatus.Queued" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="queued")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobStatus</ReturnType>
      </ReturnValue>
      <MemberValue>7</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f73a3-106">ジョブが実行 (depricated にキュー入れられたのシノニム) のキューにあることを示します</span><span class="sxs-lookup"><span data-stu-id="f73a3-106">Indicates that a Job is in the queue for execution (synonym for enqueued to be depricated)</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="Running" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.JobStatus Running = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.JobStatus.Running" />
      <MemberSignature Language="VB.NET" Value="Running" />
      <MemberSignature Language="F#" Value="Running = 2" Usage="Microsoft.Azure.Devices.JobStatus.Running" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="running")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f73a3-107">ジョブが実行されていることを示します</span><span class="sxs-lookup"><span data-stu-id="f73a3-107">Indicates that a Job is running</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Scheduled">
      <MemberSignature Language="C#" Value="Scheduled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.JobStatus Scheduled = int32(6)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.JobStatus.Scheduled" />
      <MemberSignature Language="VB.NET" Value="Scheduled" />
      <MemberSignature Language="F#" Value="Scheduled = 6" Usage="Microsoft.Azure.Devices.JobStatus.Scheduled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="scheduled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobStatus</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f73a3-108">将来の日時のジョブがスケジュールされていることを示します</span><span class="sxs-lookup"><span data-stu-id="f73a3-108">Indicates that a Job is scheduled for a future datetime</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="Unknown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.JobStatus Unknown = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.JobStatus.Unknown" />
      <MemberSignature Language="VB.NET" Value="Unknown" />
      <MemberSignature Language="F#" Value="Unknown = 0" Usage="Microsoft.Azure.Devices.JobStatus.Unknown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="unknown")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f73a3-109">Unknown</span><span class="sxs-lookup"><span data-stu-id="f73a3-109">Unknown</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>