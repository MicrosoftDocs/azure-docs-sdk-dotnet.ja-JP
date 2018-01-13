<Type Name="ConnectionOrientedTransportBindingElement" FullName="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement">
  <TypeSignature Language="C#" Value="public abstract class ConnectionOrientedTransportBindingElement : System.ServiceModel.Channels.TransportBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ConnectionOrientedTransportBindingElement extends System.ServiceModel.Channels.TransportBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ConnectionOrientedTransportBindingElement&#xA;Inherits TransportBindingElement" />
  <TypeSignature Language="F#" Value="type ConnectionOrientedTransportBindingElement = class&#xA;    inherit TransportBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Channels.TransportBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>TCP や名前付きパイプなどの接続指向トランスポートに共通するプロパティを追加して基本 <see cref="T:System.ServiceModel.Channels.TransportBindingElement" /> を補完する抽象クラス。  
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CanBuildChannelFactory&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelFactory&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelFactory&lt;TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.CanBuildChannelFactory``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelFactory(Of TChannel) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelFactory : System.ServiceModel.Channels.BindingContext -&gt; bool" Usage="connectionOrientedTransportBindingElement.CanBuildChannelFactory context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TChannel" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="TChannel"></typeparam>
        <param name="context">チャネルの BindingContext します。</param>
        <summary>
            指定した種類のチャネル ファクトリを作成できるかどうかを判断します。
            </summary>
        <returns>true の場合、IChannelListener&lt;TChannel&gt;の型 IChannel できるは、それ以外のバインド要素によって作成 false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanBuildChannelListener&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelListener&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context) where TChannel : class, System.ServiceModel.Channels.IChannel;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelListener&lt;class (class System.ServiceModel.Channels.IChannel) TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.CanBuildChannelListener``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelListener(Of TChannel As {Class, IChannel}) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelListener : System.ServiceModel.Channels.BindingContext -&gt; bool (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)" Usage="connectionOrientedTransportBindingElement.CanBuildChannelListener context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TChannel">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
            <InterfaceName>System.ServiceModel.Channels.IChannel</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="TChannel"></typeparam>
        <param name="context">バインド要素のコンテキストを提供するバインディング コンテキスト。</param>
        <summary>
            指定した種類のチャネルに対するリスナーをバインド要素が作成できるかどうかを示す値を返します。
            </summary>
        <returns>true の場合、IChannelListener&lt;TChannel&gt;の型 IChannel できるは、それ以外のバインド要素によって作成 false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChannelInitializationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ChannelInitializationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ChannelInitializationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.ChannelInitializationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ChannelInitializationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ChannelInitializationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.ChannelInitializationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはチャネルの初期化がタイムアウトするまでに完了する時間を指定する timespan を設定します。</summary>
        <value>返します、<see cref="T:System.TimeSpan" />タイムアウトになった後、初期化します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionBufferSize">
      <MemberSignature Language="C#" Value="public int ConnectionBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ConnectionBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.ConnectionBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.ConnectionBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.ConnectionBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得し、クライアントまたはサービスからネットワークでシリアル化されたメッセージのチャンクの送信に使用されるバッファーのサイズを設定します。 </summary>
        <value>接続バッファーのサイズ。 既定値は 8192 バイトです。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">値が 0 未満です。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetProperty&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T GetProperty&lt;T&gt; (System.ServiceModel.Channels.BindingContext context) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T GetProperty&lt;class T&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.GetProperty``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetProperty(Of T As Class) (context As BindingContext) As T" />
      <MemberSignature Language="F#" Value="override this.GetProperty : System.ServiceModel.Channels.BindingContext -&gt; 'T (requires 'T : null)" Usage="connectionOrientedTransportBindingElement.GetProperty context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="context">バインド要素のコンテキストを提供するバインディング コンテキスト。</param>
        <summary>
            存在する場合は、バインド スタックからプロパティを取得します。
            </summary>
        <returns>存在する場合は null が見つからない場合、バインド スタックからオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>URI で一致する場合にサービスに到達するためにホスト名を使用するかどうかを示す値を取得または設定します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.HostNameComparisonMode" />サービスに到達するホスト名を使用するかどうかを決定します。 既定値は、StrongWildCard で、比較にホスト名とポート番号は無視されます。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">値は、有効な HostnameComparisonMode ではありません。 </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>使用するバッファーの最大サイズを取得または設定します。</summary>
        <value>メモリ内で入力メッセージのバッファーに使用される最大バイト数。 既定値は 65,536 バイトです。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">値が 0 以下です。</exception>
      </Docs>
    </Member>
    <Member MemberName="MaxOutputDelay">
      <MemberSignature Language="C#" Value="public TimeSpan MaxOutputDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxOutputDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxOutputDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxOutputDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxOutputDelay : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxOutputDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージのチャンクまたは完全なメッセージを、送信前にメモリ内のバッファーに残したままにできる最長期間を取得または設定します。</summary>
        <value>返します、<see cref="T:System.TimeSpan" />送信する前にメッセージまたは完全なメッセージのチャンクを内のバッファー メモリに保持できる最長期間を指定します。既定値は、2 秒です。 このプロパティは、送信メッセージの AllowedOutputBatching プロパティが設定されている場合にのみ意味を true にします。 それ以外の場合は、この値は無視され、メッセージは直ちに送信されます。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">値が 0 未満です。</exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPendingAccepts">
      <MemberSignature Language="C#" Value="public int MaxPendingAccepts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPendingAccepts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxPendingAccepts" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPendingAccepts As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPendingAccepts : int with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxPendingAccepts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>サービスに対する着信接続処理に使用できる保留中の非同期受け入れ操作の最大数を取得または設定します。</summary>
        <value>サービスが同時に許可できる接続の最大数。 既定値は 1 です。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">値が 0 以下です。</exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPendingConnections">
      <MemberSignature Language="C#" Value="public int MaxPendingConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPendingConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxPendingConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPendingConnections As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPendingConnections : int with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.MaxPendingConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>サービスでディスパッチを待機している最大接続数を取得または設定します。</summary>
        <value>サービスでのディスパッチを待機している着信接続の最大数。 既定値は 10 です。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">値が 0 以下です。</exception>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement.TransferMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.TransferMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>接続指向のトランスポートでメッセージをバッファーするか、ストリーム配信するかを指定する値を取得または設定します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.TransferMode" />ストリームまたはバッファー モードのメッセージ転送のチャネルを使用するかどうかを示します。 既定値はバッファーです。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">値は、有効な TransferMode ではありません。</exception>
      </Docs>
    </Member>
  </Members>
</Type>