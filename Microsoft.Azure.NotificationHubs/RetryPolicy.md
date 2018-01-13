<Type Name="RetryPolicy" FullName="Microsoft.Azure.NotificationHubs.RetryPolicy">
  <TypeSignature Language="C#" Value="public abstract class RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit RetryPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.RetryPolicy" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class RetryPolicy" />
  <TypeSignature Language="F#" Value="type RetryPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>信頼性の低いアクションおよび一時的な問題には、この再試行メカニズムでの基本実装を提供します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.NotificationHubs.RetryPolicy Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.NotificationHubs.RetryPolicy Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RetryPolicy.Clone" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function Clone () As RetryPolicy" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; Microsoft.Azure.NotificationHubs.RetryPolicy" Usage="retryPolicy.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.RetryPolicy</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>新しいコピーを作成<see cref="T:Microsoft.Azure.NotificationHubs.RetryPolicy" />です。</summary>
        <returns>新しいコピー<see cref="T:Microsoft.Azure.NotificationHubs.RetryPolicy" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.RetryPolicy Default { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.NotificationHubs.RetryPolicy Default" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RetryPolicy.Default" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Default As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.Default : Microsoft.Azure.NotificationHubs.RetryPolicy" Usage="Microsoft.Azure.NotificationHubs.RetryPolicy.Default" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>ポリシーに関連付けられている既定のポリシーを取得します。</summary>
        <value>ポリシーに関連付けられている既定のポリシー。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRetryableException">
      <MemberSignature Language="C#" Value="protected abstract bool IsRetryableException (Exception lastException);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool IsRetryableException(class System.Exception lastException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RetryPolicy.IsRetryableException(System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function IsRetryableException (lastException As Exception) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsRetryableException : Exception -&gt; bool" Usage="retryPolicy.IsRetryableException lastException" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="lastException">最新バージョンが発生した例外。</param>
        <summary>エラーが発生した後に再試行が許可されているかどうかを指定します。</summary>
        <returns>例外の後に再試行が許可されている場合は true。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NoRetry">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.RetryPolicy NoRetry { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.NotificationHubs.RetryPolicy NoRetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RetryPolicy.NoRetry" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property NoRetry As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.NoRetry : Microsoft.Azure.NotificationHubs.RetryPolicy" Usage="Microsoft.Azure.NotificationHubs.RetryPolicy.NoRetry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>実行再試行再試行ポリシーを取得しません。</summary>
        <value>再試行ポリシーを実行しない再試行をします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnShouldRetry">
      <MemberSignature Language="C#" Value="protected abstract bool OnShouldRetry (TimeSpan remainingTime, int currentRetryCount, out TimeSpan retryInterval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnShouldRetry(valuetype System.TimeSpan remainingTime, int32 currentRetryCount, [out] valuetype System.TimeSpan&amp; retryInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RetryPolicy.OnShouldRetry(System.TimeSpan,System.Int32,System.TimeSpan@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnShouldRetry (remainingTime As TimeSpan, currentRetryCount As Integer, ByRef retryInterval As TimeSpan) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member OnShouldRetry : TimeSpan * int *  -&gt; bool" Usage="retryPolicy.OnShouldRetry (remainingTime, currentRetryCount, retryInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="currentRetryCount">再試行の合計数。</param>
        <param name="retryInterval">再試行の間隔。</param>
        <summary>ポリシーが再試行を許可するかどうかを指定します。</summary>
        <returns>true の場合は、ポリシーで再試行; は、それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>