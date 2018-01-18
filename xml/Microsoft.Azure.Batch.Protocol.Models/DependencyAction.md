<Type Name="DependencyAction" FullName="Microsoft.Azure.Batch.Protocol.Models.DependencyAction">
  <TypeSignature Language="C#" Value="public enum DependencyAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed DependencyAction extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.DependencyAction" />
  <TypeSignature Language="VB.NET" Value="Public Enum DependencyAction" />
  <TypeSignature Language="F#" Value="type DependencyAction = " />
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
            <span data-ttu-id="90851-101">DependencyAction の値を定義します。</span><span class="sxs-lookup"><span data-stu-id="90851-101">Defines values for DependencyAction.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Block">
      <MemberSignature Language="C#" Value="Block" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.DependencyAction Block = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.DependencyAction.Block" />
      <MemberSignature Language="VB.NET" Value="Block" />
      <MemberSignature Language="F#" Value="Block = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.DependencyAction.Block" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="block")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.DependencyAction</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="90851-102">タスクの依存関係をブロックします。</span><span class="sxs-lookup"><span data-stu-id="90851-102">Block the task's dependencies.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Satisfy">
      <MemberSignature Language="C#" Value="Satisfy" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.DependencyAction Satisfy = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.DependencyAction.Satisfy" />
      <MemberSignature Language="VB.NET" Value="Satisfy" />
      <MemberSignature Language="F#" Value="Satisfy = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.DependencyAction.Satisfy" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="satisfy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.DependencyAction</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="90851-103">タスクの依存関係を満たしています。</span><span class="sxs-lookup"><span data-stu-id="90851-103">Satisfy the task's dependencies.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>