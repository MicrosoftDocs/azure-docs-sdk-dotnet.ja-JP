<Type Name="RequestResult" FullName="Microsoft.Azure.Batch.Common.RequestResult">
  <TypeSignature Language="C#" Value="public sealed class RequestResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RequestResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.RequestResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RequestResult" />
  <TypeSignature Language="F#" Value="type RequestResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            物理的な要求の結果を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestResult (Microsoft.Azure.Batch.Common.RequestInformation requestInformation, Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Common.RequestInformation requestInformation, class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.RequestResult.#ctor(Microsoft.Azure.Batch.Common.RequestInformation,System.Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Common.RequestResult : Microsoft.Azure.Batch.Common.RequestInformation * Exception -&gt; Microsoft.Azure.Batch.Common.RequestResult" Usage="new Microsoft.Azure.Batch.Common.RequestResult (requestInformation, exception)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="requestInformation" Type="Microsoft.Azure.Batch.Common.RequestInformation" />
        <Parameter Name="exception" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="requestInformation">個々 の要求に関連付けられている情報。</param>
        <param name="exception">要求 (または例外がない場合は null) の実行中にヒットする例外。</param>
        <summary>
            新しい <see cref="T:Microsoft.Azure.Batch.Common.RequestResult" /> を初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.RequestResult.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="Microsoft.Azure.Batch.Common.RequestResult.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            存在する場合は、ヒットして要求の実行中に例外を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.RequestInformation RequestInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Common.RequestInformation RequestInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.RequestResult.RequestInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestInformation As RequestInformation" />
      <MemberSignature Language="F#" Value="member this.RequestInformation : Microsoft.Azure.Batch.Common.RequestInformation" Usage="Microsoft.Azure.Batch.Common.RequestResult.RequestInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.RequestInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求に関する情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Task">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task Task { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Threading.Tasks.Task Task" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.RequestResult.Task" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Task As Task" />
      <MemberSignature Language="F#" Value="member this.Task : System.Threading.Tasks.Task" Usage="Microsoft.Azure.Batch.Common.RequestResult.Task" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="T:System.Threading.Tasks.Task" />要求に関連付けられているオブジェクト。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>