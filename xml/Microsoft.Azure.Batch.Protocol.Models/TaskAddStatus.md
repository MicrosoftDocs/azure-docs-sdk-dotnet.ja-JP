<Type Name="TaskAddStatus" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus">
  <TypeSignature Language="C#" Value="public enum TaskAddStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TaskAddStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum TaskAddStatus" />
  <TypeSignature Language="F#" Value="type TaskAddStatus = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f7c7d-101">TaskAddStatus の値を定義します。</span><span class="sxs-lookup"><span data-stu-id="f7c7d-101">Defines values for TaskAddStatus.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ClientError">
      <MemberSignature Language="C#" Value="ClientError" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus ClientError = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus.ClientError" />
      <MemberSignature Language="VB.NET" Value="ClientError" />
      <MemberSignature Language="F#" Value="ClientError = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus.ClientError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="clienterror")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7c7d-102">タスクをクライアント エラーのため追加できませんでしたし、必要に応じて要求を変更することがなくは再試行されません必要があります。</span><span class="sxs-lookup"><span data-stu-id="f7c7d-102">The task failed to add due to a client error and should not be retried without modifying the request as appropriate.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ServerError">
      <MemberSignature Language="C#" Value="ServerError" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus ServerError = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus.ServerError" />
      <MemberSignature Language="VB.NET" Value="ServerError" />
      <MemberSignature Language="F#" Value="ServerError = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus.ServerError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="servererror")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7c7d-103">タスクは、サーバー エラーが追加に失敗し、変更せずに再試行することができます。</span><span class="sxs-lookup"><span data-stu-id="f7c7d-103">Task failed to add due to a server error and can be retried without modification.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Success">
      <MemberSignature Language="C#" Value="Success" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus Success = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus.Success" />
      <MemberSignature Language="VB.NET" Value="Success" />
      <MemberSignature Language="F#" Value="Success = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus.Success" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="success")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7c7d-104">タスクが正常に追加されました。</span><span class="sxs-lookup"><span data-stu-id="f7c7d-104">The task was added successfully.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>