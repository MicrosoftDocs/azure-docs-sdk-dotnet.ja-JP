<Type Name="DisableJobOption" FullName="Microsoft.Azure.Batch.Protocol.Models.DisableJobOption">
  <TypeSignature Language="C#" Value="public enum DisableJobOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed DisableJobOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.DisableJobOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum DisableJobOption" />
  <TypeSignature Language="F#" Value="type DisableJobOption = " />
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
            <span data-ttu-id="76615-101">DisableJobOption の値を定義します。</span><span class="sxs-lookup"><span data-stu-id="76615-101">Defines values for DisableJobOption.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Requeue">
      <MemberSignature Language="C#" Value="Requeue" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.DisableJobOption Requeue = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.DisableJobOption.Requeue" />
      <MemberSignature Language="VB.NET" Value="Requeue" />
      <MemberSignature Language="F#" Value="Requeue = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.DisableJobOption.Requeue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="requeue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.DisableJobOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="76615-102">タスクの実行を終了し、そのキューに再登録します。</span><span class="sxs-lookup"><span data-stu-id="76615-102">Terminate running tasks and requeue them.</span></span> <span data-ttu-id="76615-103">このタスクは、ジョブが有効になると再び実行されます。</span><span class="sxs-lookup"><span data-stu-id="76615-103">The tasks will run again when the job is enabled.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="Terminate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.DisableJobOption Terminate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.DisableJobOption.Terminate" />
      <MemberSignature Language="VB.NET" Value="Terminate" />
      <MemberSignature Language="F#" Value="Terminate = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.DisableJobOption.Terminate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="terminate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.DisableJobOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="76615-104">タスクの実行を終了します。</span><span class="sxs-lookup"><span data-stu-id="76615-104">Terminate running tasks.</span></span> <span data-ttu-id="76615-105">終了しましたが再実行されないことを示す failureInfo には、タスクが完了します。</span><span class="sxs-lookup"><span data-stu-id="76615-105">The tasks will be completed with failureInfo indicating that they were terminated, and will not run again.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Wait">
      <MemberSignature Language="C#" Value="Wait" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.DisableJobOption Wait = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.DisableJobOption.Wait" />
      <MemberSignature Language="VB.NET" Value="Wait" />
      <MemberSignature Language="F#" Value="Wait = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.DisableJobOption.Wait" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="wait")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.DisableJobOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="76615-106">実行中のタスクを完了できるようにします。</span><span class="sxs-lookup"><span data-stu-id="76615-106">Allow currently running tasks to complete.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>