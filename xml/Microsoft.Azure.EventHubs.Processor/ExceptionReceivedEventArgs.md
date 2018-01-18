<Type Name="ExceptionReceivedEventArgs" FullName="Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs">
  <TypeSignature Language="C#" Value="public sealed class ExceptionReceivedEventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExceptionReceivedEventArgs extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExceptionReceivedEventArgs" />
  <TypeSignature Language="F#" Value="type ExceptionReceivedEventArgs = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e002d-101"><see cref="M:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.NotifyOfException(System.String,System.String,System.Exception,System.String)" /> イベントのデータを提供します。</span><span class="sxs-lookup"><span data-stu-id="e002d-101">Provides data for the <see cref="M:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.NotifyOfException(System.String,System.String,System.Exception,System.String)" /> event.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public string Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As String" />
      <MemberSignature Language="F#" Value="member this.Action : string" Usage="Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e002d-102">どのような一般的なアクティビティが例外をスローしたかを示す短い文字列。</span><span class="sxs-lookup"><span data-stu-id="e002d-102">A short string that indicates what general activity threw the exception.</span></span>
            <span data-ttu-id="e002d-103">使用可能な値の一覧については、EventProcessorHostActionString を参照してください。</span><span class="sxs-lookup"><span data-stu-id="e002d-103">See EventProcessorHostActionString for a list of possible values.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e002d-104">スローされた例外。</span><span class="sxs-lookup"><span data-stu-id="e002d-104">The exception that was thrown.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Hostname">
      <MemberSignature Language="C#" Value="public string Hostname { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Hostname" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs.Hostname" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Hostname As String" />
      <MemberSignature Language="F#" Value="member this.Hostname : string" Usage="Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs.Hostname" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e002d-105">により、複数のホストの 1 つのプロセスでエラーの発生元を区別できます。</span><span class="sxs-lookup"><span data-stu-id="e002d-105">Allows distinguishing the error source if multiple hosts in a single process.</span></span>
            </summary>
        <value><span data-ttu-id="e002d-106">例外が発生したため、ホストの名前。</span><span class="sxs-lookup"><span data-stu-id="e002d-106">The name of the host that experienced the exception.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e002d-107">により、複数のホストの 1 つのプロセスでエラーの発生元を区別できます。</span><span class="sxs-lookup"><span data-stu-id="e002d-107">Allows distinguishing the error source if multiple hosts in a single process.</span></span>
            </summary>
        <value><span data-ttu-id="e002d-108">例外が発生したため、パーティション id です。</span><span class="sxs-lookup"><span data-stu-id="e002d-108">The partition id that experienced the exception.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>