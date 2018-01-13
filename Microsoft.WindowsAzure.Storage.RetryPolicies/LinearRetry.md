<Type Name="LinearRetry" FullName="Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry">
  <TypeSignature Language="C#" Value="public sealed class LinearRetry : Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit LinearRetry extends System.Object implements class Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LinearRetry&#xA;Implements IExtendedRetryPolicy" />
  <TypeSignature Language="F#" Value="type LinearRetry = class&#xA;    interface IExtendedRetryPolicy&#xA;    interface IRetryPolicy" />
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
      <InterfaceName>Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            指定された回数の再試行の間の一定の時間を指定した期間を使用して、再試行を実行する再試行ポリシーを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinearRetry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry.#ctor" />
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
            <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinearRetry (TimeSpan deltaBackoff, int maxAttempts);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan deltaBackoff, int32 maxAttempts) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry.#ctor(System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deltaBackoff As TimeSpan, maxAttempts As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry : TimeSpan * int -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry" Usage="new Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry (deltaBackoff, maxAttempts)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deltaBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxAttempts" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="deltaBackoff">A<see cref="T:System.TimeSpan" />再試行のバックオフ間隔を指定します。</param>
        <param name="maxAttempts">再試行の最大数を指定する整数。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry" />クラスの指定されたデルタと再試行の最大数を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateInstance">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy CreateInstance ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy CreateInstance() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry.CreateInstance" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateInstance () As IRetryPolicy" />
      <MemberSignature Language="F#" Value="abstract member CreateInstance : unit -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy&#xA;override this.CreateInstance : unit -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" Usage="linearRetry.CreateInstance " />
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
    <Member MemberName="Evaluate">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo Evaluate (Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext retryContext, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo Evaluate(class Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext retryContext, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry.Evaluate(Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Evaluate : Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo&#xA;override this.Evaluate : Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" Usage="linearRetry.Evaluate (retryContext, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy.Evaluate(Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="retryContext" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="retryContext">A<see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" />オブジェクトの数を示す再試行回数、前回の要求の結果と、次の再試行するかどうか、プライマリまたはセカンダリの場所で発生する必要があり、配置モードを指定します。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            次の再試行まで、操作を再試行するかどうかと間隔を決定します。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" />配置モードを示すオブジェクトのプライマリまたはセカンダリの場所に、次の再試行が発生するかどうかとします。 場合<c>null</c>操作は再試行されません。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public bool ShouldRetry (int currentRetryCount, int statusCode, Exception lastException, out TimeSpan retryInterval, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ShouldRetry(int32 currentRetryCount, int32 statusCode, class System.Exception lastException, [out] valuetype System.TimeSpan&amp; retryInterval, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry.ShouldRetry(System.Int32,System.Int32,System.Exception,System.TimeSpan@,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ShouldRetry : int * int * Exception *  * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.ShouldRetry : int * int * Exception *  * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="linearRetry.ShouldRetry (currentRetryCount, statusCode, lastException, retryInterval, operationContext)" />
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
            次の再試行まで、操作を再試行するかどうかと間隔を決定します。
            </summary>
        <returns>
          <c>true</c>場合は、操作は、それ以外の再試行をする必要があります<c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>