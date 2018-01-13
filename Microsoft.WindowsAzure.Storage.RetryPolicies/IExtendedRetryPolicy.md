<Type Name="IExtendedRetryPolicy" FullName="Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy">
  <TypeSignature Language="C#" Value="public interface IExtendedRetryPolicy : Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IExtendedRetryPolicy implements class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Interface IExtendedRetryPolicy&#xA;Implements IRetryPolicy" />
  <TypeSignature Language="F#" Value="type IExtendedRetryPolicy = interface&#xA;    interface IRetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            再試行ポリシーを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Evaluate">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo Evaluate (Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext retryContext, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo Evaluate(class Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext retryContext, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy.Evaluate(Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Evaluate : Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" Usage="iExtendedRetryPolicy.Evaluate (retryContext, operationContext)" />
      <MemberType>Method</MemberType>
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
  </Members>
</Type>