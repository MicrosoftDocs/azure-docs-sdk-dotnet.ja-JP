<Type Name="OperationRetrySettings" FullName="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings">
  <TypeSignature Language="C#" Value="public sealed class OperationRetrySettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit OperationRetrySettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class OperationRetrySettings" />
  <TypeSignature Language="F#" Value="type OperationRetrySettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            クライアントとサービスのレプリカ間の通信チャネルでの例外で要求の再試行ポリシーを指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationRetrySettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            再試行の設定の既定値を持つ OperationRetrySettings をインスタンス化します。
            MaxRetryBackoffIntervalOnTransientErrors、NonTransientErrors の既定値は、2 秒です。 MaxRetryCount の既定値は 10 です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationRetrySettings (TimeSpan maxRetryBackoffIntervalOnTransientErrors, TimeSpan maxRetryBackoffIntervalOnNonTransientErrors, int defaultMaxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan maxRetryBackoffIntervalOnTransientErrors, valuetype System.TimeSpan maxRetryBackoffIntervalOnNonTransientErrors, int32 defaultMaxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.#ctor(System.TimeSpan,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxRetryBackoffIntervalOnTransientErrors As TimeSpan, maxRetryBackoffIntervalOnNonTransientErrors As TimeSpan, defaultMaxRetryCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings : TimeSpan * TimeSpan * int -&gt; Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings (maxRetryBackoffIntervalOnTransientErrors, maxRetryBackoffIntervalOnNonTransientErrors, defaultMaxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxRetryBackoffIntervalOnTransientErrors" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffIntervalOnNonTransientErrors" Type="System.TimeSpan" />
        <Parameter Name="defaultMaxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxRetryBackoffIntervalOnTransientErrors">
            バックオフ一時的なエラーの発生時の再試行前にする最大間隔を指定します。
            </param>
        <param name="maxRetryBackoffIntervalOnNonTransientErrors">
            バックオフ非一時的なエラーの発生時の再試行前にする最大間隔を指定します。
            </param>
        <param name="defaultMaxRetryCount">
            再試行の回数の最大数を指定します。
            </param>
        <summary>
            指定した設定と OperationRetrySettings をインスタンス化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMaxRetryCount">
      <MemberSignature Language="C#" Value="public int DefaultMaxRetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DefaultMaxRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.DefaultMaxRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultMaxRetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DefaultMaxRetryCount : int" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.DefaultMaxRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            再試行の回数の最大数を指定します。
            </summary>
        <value>特定の例外の再試行の回数の最大数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryBackoffIntervalOnNonTransientErrors">
      <MemberSignature Language="C#" Value="public TimeSpan MaxRetryBackoffIntervalOnNonTransientErrors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxRetryBackoffIntervalOnNonTransientErrors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnNonTransientErrors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxRetryBackoffIntervalOnNonTransientErrors As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxRetryBackoffIntervalOnNonTransientErrors : TimeSpan" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnNonTransientErrors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            非一時的なエラーの場合に再試行する前にバックオフする最大間隔を指定します。
            </summary>
        <value>非一時的なエラーでバックオフする再試行の最大間隔</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryBackoffIntervalOnTransientErrors">
      <MemberSignature Language="C#" Value="public TimeSpan MaxRetryBackoffIntervalOnTransientErrors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxRetryBackoffIntervalOnTransientErrors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxRetryBackoffIntervalOnTransientErrors As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxRetryBackoffIntervalOnTransientErrors : TimeSpan" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            一時的なエラーの場合に再試行する前にバックオフする最大間隔を指定します。
            </summary>
        <value>一時的なエラーでバックオフする再試行の最大間隔</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>