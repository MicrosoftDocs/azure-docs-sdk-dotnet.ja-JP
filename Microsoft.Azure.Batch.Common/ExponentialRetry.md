<Type Name="ExponentialRetry" FullName="Microsoft.Azure.Batch.Common.ExponentialRetry">
  <TypeSignature Language="C#" Value="public class ExponentialRetry : Microsoft.Azure.Batch.Common.IRetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExponentialRetry extends System.Object implements class Microsoft.Azure.Batch.Common.IRetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.ExponentialRetry" />
  <TypeSignature Language="VB.NET" Value="Public Class ExponentialRetry&#xA;Implements IRetryPolicy" />
  <TypeSignature Language="F#" Value="type ExponentialRetry = class&#xA;    interface IRetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.Common.IRetryPolicy</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            指定された回数の再試行、指数バックオフ方式を使用して、再試行の間隔を決定するを実行する再試行ポリシーを表します。 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExponentialRetry (TimeSpan deltaBackoff, int maxRetries);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan deltaBackoff, int32 maxRetries) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.ExponentialRetry.#ctor(System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deltaBackoff As TimeSpan, maxRetries As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Common.ExponentialRetry : TimeSpan * int -&gt; Microsoft.Azure.Batch.Common.ExponentialRetry" Usage="new Microsoft.Azure.Batch.Common.ExponentialRetry (deltaBackoff, maxRetries)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deltaBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxRetries" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="deltaBackoff">ここで、結果として得られるバックオフは 2、再試行のバックオフ間隔 ^ n * deltaBackoff (n は再試行の回数)</param>
        <param name="maxRetries">再試行の最大数。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.Common.ExponentialRetry" />クラスの指定されたデルタと再試行の最大数を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeltaBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan DeltaBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DeltaBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.ExponentialRetry.DeltaBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeltaBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DeltaBackoff : TimeSpan" Usage="Microsoft.Azure.Batch.Common.ExponentialRetry.DeltaBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ここで、結果として得られるバックオフは 2、再試行のバックオフ間隔を取得 ^ n * deltaBackoff (n は再試行の回数)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumRetries">
      <MemberSignature Language="C#" Value="public int MaximumRetries { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaximumRetries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.ExponentialRetry.MaximumRetries" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumRetries As Integer" />
      <MemberSignature Language="F#" Value="member this.MaximumRetries : int" Usage="Microsoft.Azure.Batch.Common.ExponentialRetry.MaximumRetries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            再試行の最大数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Common.RetryDecision&gt; ShouldRetryAsync (Exception exception, Microsoft.Azure.Batch.Common.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Common.RetryDecision&gt; ShouldRetryAsync(class System.Exception exception, class Microsoft.Azure.Batch.Common.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.ExponentialRetry.ShouldRetryAsync(System.Exception,Microsoft.Azure.Batch.Common.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ShouldRetryAsync : Exception * Microsoft.Azure.Batch.Common.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Common.RetryDecision&gt;&#xA;override this.ShouldRetryAsync : Exception * Microsoft.Azure.Batch.Common.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Common.RetryDecision&gt;" Usage="exponentialRetry.ShouldRetryAsync (exception, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.Common.IRetryPolicy.ShouldRetryAsync(System.Exception,Microsoft.Azure.Batch.Common.OperationContext)</InterfaceMember>
      </Implements>
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