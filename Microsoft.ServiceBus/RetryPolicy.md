<Type Name="RetryPolicy" FullName="Microsoft.ServiceBus.RetryPolicy">
  <TypeSignature Language="C#" Value="public abstract class RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit RetryPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.RetryPolicy" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class RetryPolicy" />
  <TypeSignature Language="F#" Value="type RetryPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            メッセージング操作を再試行するための抽象化を表します。 ユーザーは、このクラスを実装する必要があり、代わりにする必要がありますを使用して、指定した実装のいずれか。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceBus.RetryPolicy Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.RetryPolicy Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.Clone" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function Clone () As RetryPolicy" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; Microsoft.ServiceBus.RetryPolicy" Usage="retryPolicy.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RetryPolicy</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>現在の新しいコピーを作成<see cref="T:Microsoft.ServiceBus.RetryPolicy" />し、新しいインスタンスを複製します。</summary>
        <returns>新しいコピー<see cref="T:Microsoft.ServiceBus.RetryPolicy" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.RetryPolicy Default { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.ServiceBus.RetryPolicy Default" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RetryPolicy.Default" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Default As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.Default : Microsoft.ServiceBus.RetryPolicy" Usage="Microsoft.ServiceBus.RetryPolicy.Default" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            インスタンスを取得、<see cref="T:Microsoft.ServiceBus.RetryExponential" />再試行ポリシーで、メッセージング操作の再試行間隔が指数関数的に高くなるという既定の設定を提供します。 このプロパティがアクセスされるたびに新しいインスタンスが作成されます。
            </summary>
        <value>ポリシーに関連付けられている既定のポリシー。</value>
        <remarks>このプロパティは実質的に次のインスタンスを作成しています。
            <code>
               var policy = new RetryExponential(
                                    TimeSpan.Zero,
                                    TimeSpan.FromSeconds(30),
                                    10);                 
            </code>
            
            再試行ポリシーが常に受け入れる必要があることを確認することが重要、<seealso cref="P:Microsoft.ServiceBus.Messaging.ClientEntity.OperationTimeout" />のため、次の再試行間隔が操作に時間を超える場合、その再試行が終了されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRetryableException">
      <MemberSignature Language="C#" Value="protected abstract bool IsRetryableException (Exception lastException);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool IsRetryableException(class System.Exception lastException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.IsRetryableException(System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function IsRetryableException (lastException As Exception) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsRetryableException : Exception -&gt; bool" Usage="retryPolicy.IsRetryableException lastException" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="lastException">最新バージョンが発生した例外。</param>
        <summary>指定された例外の後に再試行する許されるかどうかを判断します。</summary>
        <returns>このメソッドが false を返す場合は、再試行は行われません。 それ以外の場合、<see cref="M:Microsoft.ServiceBus.RetryPolicy.OnShouldRetry(System.TimeSpan,System.Int32,System.TimeSpan@)" />メソッドは、再試行するタイミングを決定します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NoRetry">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.RetryPolicy NoRetry { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.ServiceBus.RetryPolicy NoRetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RetryPolicy.NoRetry" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property NoRetry As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.NoRetry : Microsoft.ServiceBus.RetryPolicy" Usage="Microsoft.ServiceBus.RetryPolicy.NoRetry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            インスタンスを取得、<see cref="P:Microsoft.ServiceBus.RetryPolicy.NoRetry" />再試行ポリシーを効果的に再試行を有効にします。
            たびにこのプロパティにアクセスすると、新しいインスタンスが返されます。
            </summary>
        <value>再試行ポリシーを実行しない再試行をします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnShouldRetry">
      <MemberSignature Language="C#" Value="protected abstract bool OnShouldRetry (TimeSpan remainingTime, int currentRetryCount, out TimeSpan retryInterval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnShouldRetry(valuetype System.TimeSpan remainingTime, int32 currentRetryCount, [out] valuetype System.TimeSpan&amp; retryInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.OnShouldRetry(System.TimeSpan,System.Int32,System.TimeSpan@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnShouldRetry (remainingTime As TimeSpan, currentRetryCount As Integer, ByRef retryInterval As TimeSpan) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member OnShouldRetry : TimeSpan * int *  -&gt; bool" Usage="retryPolicy.OnShouldRetry (remainingTime, currentRetryCount, retryInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="remainingTime" Type="System.TimeSpan" />
        <Parameter Name="currentRetryCount" Type="System.Int32" />
        <Parameter Name="retryInterval" Type="System.TimeSpan&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="remainingTime">残り時間です。</param>
        <param name="currentRetryCount">再試行回数の合計です。</param>
        <param name="retryInterval">再試行の間隔。</param>
        <summary>再試行ポリシーの再試行間隔を計算します。</summary>
        <returns>等しい時間の時間が、スレッドがアイドル状態になった後に再試行操作が発生した場合、このメソッドは、true を返します、<paramref name="retryInterval" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetServerBusyInternal">
      <MemberSignature Language="C#" Value="protected virtual void ResetServerBusyInternal ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void ResetServerBusyInternal() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.ResetServerBusyInternal" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub ResetServerBusyInternal ()" />
      <MemberSignature Language="F#" Value="abstract member ResetServerBusyInternal : unit -&gt; unit&#xA;override this.ResetServerBusyInternal : unit -&gt; unit" Usage="retryPolicy.ResetServerBusyInternal " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServerBusy">
      <MemberSignature Language="C#" Value="protected void SetServerBusy (string exceptionMessage);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void SetServerBusy(string exceptionMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.SetServerBusy(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub SetServerBusy (exceptionMessage As String)" />
      <MemberSignature Language="F#" Value="member this.SetServerBusy : string -&gt; unit" Usage="retryPolicy.SetServerBusy exceptionMessage" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exceptionMessage" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="exceptionMessage"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServerBusyInternal">
      <MemberSignature Language="C#" Value="protected virtual void SetServerBusyInternal ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void SetServerBusyInternal() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.SetServerBusyInternal" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub SetServerBusyInternal ()" />
      <MemberSignature Language="F#" Value="abstract member SetServerBusyInternal : unit -&gt; unit&#xA;override this.SetServerBusyInternal : unit -&gt; unit" Usage="retryPolicy.SetServerBusyInternal " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>