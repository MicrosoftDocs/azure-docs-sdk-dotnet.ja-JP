<Type Name="NoRetry" FullName="Microsoft.WindowsAzure.Storage.RetryPolicies.NoRetry">
  <TypeSignature Language="C#" Value="public sealed class NoRetry : Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NoRetry extends System.Object implements class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RetryPolicies.NoRetry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NoRetry&#xA;Implements IRetryPolicy" />
  <TypeSignature Language="F#" Value="type NoRetry = class&#xA;    interface IRetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            実行再試行再試行ポリシーを表しません。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NoRetry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.NoRetry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.NoRetry" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateInstance">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy CreateInstance ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy CreateInstance() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.NoRetry.CreateInstance" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateInstance () As IRetryPolicy" />
      <MemberSignature Language="F#" Value="abstract member CreateInstance : unit -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy&#xA;override this.CreateInstance : unit -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" Usage="noRetry.CreateInstance " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy.CreateInstance</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在試行中の要求の新しい再試行ポリシーを生成します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />を試行中、現在の要求の再試行ポリシーを表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public bool ShouldRetry (int currentRetryCount, int statusCode, Exception lastException, out TimeSpan retryInterval, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ShouldRetry(int32 currentRetryCount, int32 statusCode, class System.Exception lastException, [out] valuetype System.TimeSpan&amp; retryInterval, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.NoRetry.ShouldRetry(System.Int32,System.Int32,System.Exception,System.TimeSpan@,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ShouldRetry : int * int * Exception *  * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.ShouldRetry : int * int * Exception *  * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="noRetry.ShouldRetry (currentRetryCount, statusCode, lastException, retryInterval, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy.ShouldRetry(System.Int32,System.Int32,System.Exception,System.TimeSpan@,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentRetryCount" Type="System.Int32" />
        <Parameter Name="statusCode" Type="System.Int32" />
        <Parameter Name="lastException" Type="System.Exception" />
        <Parameter Name="retryInterval" Type="System.TimeSpan&amp;" RefType="out" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="currentRetryCount">指定された操作の再試行の回数を指定する整数。 ゼロの値を示しますこの最初のエラーが発生しました。</param>
        <param name="statusCode">最後の操作のステータス コードを格納する整数。</param>
        <param name="lastException"><see cref="T:System.Exception" />を最後に発生した例外を表すオブジェクト。</param>
        <param name="retryInterval">A<see cref="T:System.TimeSpan" />次の再試行まで待機する間隔を示すです。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            かどうか、操作して再試行する次の再試行までの待機時間を決定します。 
            </summary>
        <returns>
          <c>true</c>場合は、操作は、それ以外の再試行をする必要があります<c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>