<Type Name="IRetryPolicy" FullName="Microsoft.Azure.Batch.Common.IRetryPolicy">
  <TypeSignature Language="C#" Value="public interface IRetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.IRetryPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRetryPolicy" />
  <TypeSignature Language="F#" Value="type IRetryPolicy = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            再試行ポリシーを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ShouldRetryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Common.RetryDecision&gt; ShouldRetryAsync (Exception exception, Microsoft.Azure.Batch.Common.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Common.RetryDecision&gt; ShouldRetryAsync(class System.Exception exception, class Microsoft.Azure.Batch.Common.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.IRetryPolicy.ShouldRetryAsync(System.Exception,Microsoft.Azure.Batch.Common.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ShouldRetryAsync : Exception * Microsoft.Azure.Batch.Common.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Common.RetryDecision&gt;" Usage="iRetryPolicy.ShouldRetryAsync (exception, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Common.RetryDecision&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Batch.Common.OperationContext" />
      </Parameters>
      <Docs>
        <param name="exception"><see cref="T:System.Exception" />を最後に発生した例外を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.Azure.Batch.Common.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            かどうか、操作して再試行する次の再試行までの待機時間を決定します。 
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.Common.RetryDecision" />再試行を実行するかどうかを指定するオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>