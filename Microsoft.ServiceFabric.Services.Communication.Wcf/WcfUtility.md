<Type Name="WcfUtility" FullName="Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility">
  <TypeSignature Language="C#" Value="public static class WcfUtility" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed WcfUtility extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfUtility" />
  <TypeSignature Language="F#" Value="type WcfUtility = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            WCF の通信に既定のバインドを作成するためのユーティリティ クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateTcpClientBinding">
      <MemberSignature Language="C#" Value="public static System.ServiceModel.Channels.Binding CreateTcpClientBinding (long maxMessageSize = 4194304, TimeSpan openTimeout = null, TimeSpan closeTimeout = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.ServiceModel.Channels.Binding CreateTcpClientBinding(int64 maxMessageSize, valuetype System.TimeSpan openTimeout, valuetype System.TimeSpan closeTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpClientBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateTcpClientBinding (Optional maxMessageSize As Long = 4194304, Optional openTimeout As TimeSpan = null, Optional closeTimeout As TimeSpan = null) As Binding" />
      <MemberSignature Language="F#" Value="static member CreateTcpClientBinding : int64 * TimeSpan * TimeSpan -&gt; System.ServiceModel.Channels.Binding" Usage="Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpClientBinding (maxMessageSize, openTimeout, closeTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.Binding</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageSize" Type="System.Int64" />
        <Parameter Name="openTimeout" Type="System.TimeSpan" />
        <Parameter Name="closeTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageSize">
                バイト単位でメッセージの最大サイズ。 値が指定されていないかである場合より小さいまたは 4,194,304 バイト (4 MB) の既定値の 0 に equals を使用します。
                </param>
        <param name="openTimeout">
                接続のオープンのタイムアウトです。 値が指定されていない場合は、5 秒間の既定値が使用されます。
                </param>
        <param name="closeTimeout">
                接続を中止する前に、接続のドレインを実行するメッセージを待機する時間です。 値が指定されていない場合は、5 秒間の既定値が使用されます。
                </param>
        <summary>
                TCP クライアントが WCF 通信のセキュリティなしのバインドを作成します。
            </summary>
        <returns><see cref="T:System.ServiceModel.Channels.Binding" /> に使用する <see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfCommunicationClientFactory`1" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTcpListenerBinding">
      <MemberSignature Language="C#" Value="public static System.ServiceModel.Channels.Binding CreateTcpListenerBinding (long maxMessageSize = 4194304, TimeSpan openTimeout = null, TimeSpan closeTimeout = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.ServiceModel.Channels.Binding CreateTcpListenerBinding(int64 maxMessageSize, valuetype System.TimeSpan openTimeout, valuetype System.TimeSpan closeTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateTcpListenerBinding (Optional maxMessageSize As Long = 4194304, Optional openTimeout As TimeSpan = null, Optional closeTimeout As TimeSpan = null) As Binding" />
      <MemberSignature Language="F#" Value="static member CreateTcpListenerBinding : int64 * TimeSpan * TimeSpan -&gt; System.ServiceModel.Channels.Binding" Usage="Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding (maxMessageSize, openTimeout, closeTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.Binding</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageSize" Type="System.Int64" />
        <Parameter Name="openTimeout" Type="System.TimeSpan" />
        <Parameter Name="closeTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageSize">
                バイト単位でメッセージの最大サイズ。 値が指定されていないかである場合より小さいまたは 4,194,304 バイト (4 MB) の既定値の 0 に equals を使用します。
                </param>
        <param name="openTimeout">
                接続のオープンのタイムアウトです。 値が指定されていない場合は、5 秒間の既定値が使用されます。
                </param>
        <param name="closeTimeout">
                接続を中止する前に、接続のドレインを実行するメッセージを待機する時間です。 値が指定されていない場合は、5 秒間の既定値が使用されます。
                </param>
        <summary>
                WCF の通信のセキュリティなしのバインドの TCP リスナーを作成します。
            </summary>
        <returns><see cref="T:System.ServiceModel.Channels.Binding" /> に使用する <see cref="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>