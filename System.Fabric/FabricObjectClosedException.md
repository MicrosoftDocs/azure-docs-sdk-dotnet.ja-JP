<Type Name="FabricObjectClosedException" FullName="System.Fabric.FabricObjectClosedException">
  <TypeSignature Language="C#" Value="public class FabricObjectClosedException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricObjectClosedException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricObjectClosedException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricObjectClosedException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricObjectClosedException = class&#xA;    inherit FabricException" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.MaintainabilityRules", "SA1402:FileMayOnlyContainASingleClass", Justification="Exception")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>
            Service Fabric オブジェクトは、次の条件のいずれかが原因の閉じられた状態で、現在場合にスローされる例外。
                1. Service Fabric オブジェクトを削除しています。
                2. Service Fabric オブジェクトは、フェールオーバーにより到達可能ではありません。
            </para>
    </summary>
    <remarks>
      <para>サービスが Service Fabric での操作を実行しようとしたときにこの例外を確認できるなど、または<see cref="T:System.Fabric.FabricReplicator" />オブジェクトが closed 状態のときにします。 別の例での API が呼び出されると、<see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にあるときです。</para>
      <para>
            処理<see cref="T:System.Fabric.FabricObjectClosedException" />の<see cref="T:System.Fabric.FabricClient" />呼び出し: FabricClient の呼び出しが表示される場合<see cref="T:System.Fabric.FabricObjectClosedException" />を参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions">FabricClient の例外処理</see>FabricClient の一般的な障害を処理するためです。
                </para>
      <para>
            処理<see cref="T:System.Fabric.FabricObjectClosedException" />の<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">信頼性の高いコレクション</see>:
                1. サービスが表示される場合<see cref="T:System.Fabric.FabricObjectClosedException" />で<see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see>、例外をキャッチしから返すか<see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see>です。
                    <see cref="T:System.Threading.CancellationToken" />に渡される<see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see>通知されるとします。 この取り消しが通知時に、すべてのバック グラウンド タスクは実行を完了する必要があります。
                    2. サービスが表示される場合<see cref="T:System.Fabric.FabricObjectClosedException" />(など、通信リスナー) 経由でクライアント要求を処理中に、サービスは、こと、新しいプライマリを見つけるために、サービスを解決する必要があります再それをクライアントに通知をクライアントに例外をスローする必要があります。
                
            [注]場合、 <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see>で削除された<see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestatemanager.removeasync?view=azure-dotnet#Microsoft_ServiceFabric_Data_IReliableStateManager_RemoveAsync_Microsoft_ServiceFabric_Data_ITransaction_System_Uri_System_TimeSpan_">IReliableStateManager.RemoveAsync()</see>、このオプションを表示しようとしています。 すべての呼び出し<see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see>はを参照してください<see cref="T:System.Fabric.FabricObjectClosedException" />です。 これらの呼び出しと同期する必要があります、 <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestatemanager.removeasync?view=azure-dotnet#Microsoft_ServiceFabric_Data_IReliableStateManager_RemoveAsync_Microsoft_ServiceFabric_Data_ITransaction_System_Uri_System_TimeSpan_">IReliableStateManager.RemoveAsync()</see>呼び出しを知っている必要がある、 <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see>は削除されました。
            このケースを処理する方法は次のとおりです。
            1. 再作成、 <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see>が削除されたし、操作をやり直してください。
            2. 無視する、 <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see>およびその他の処理<see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see>サービス。
                3. ロックを使用すると、競合を回避できます。 そのためは、削除の呼び出し場合、ユーザーの処理を停止、 <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see>さらにします。
                </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricObjectClosedException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.Unknown" />です。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException errorCode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="errorCode">
          <para>例外に関連付けられているエラー コード。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricObjectClosedException" />クラスを指定したエラー コード。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : string -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">
          <para>例外の原因を説明するエラー メッセージ。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricObjectClosedException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.Unknown" />と指定したエラー メッセージ。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricObjectClosedException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
          <para><see cref="T:System.Runtime.Serialization.SerializationInfo" />を含むオブジェクトがスローされた例外オブジェクト データをシリアル化します。</para>
        </param>
        <param name="context">
          <para>転送元または転送先に関するコンテキスト情報を格納する <see cref="T:System.Runtime.Serialization.StreamingContext" /> オブジェクト。 Context パラメーターは将来使用するために予約されており、null にすることができます。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricObjectClosedException" />コンテキストを指定して、シリアル化されたオブジェクトのデータからのクラスです。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : string * Exception -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">
          <para>例外の原因を説明するエラー メッセージ。</para>
        </param>
        <param name="inner">
          <para>内部例外が指定されていない場合、現在の例外の原因となった例外。 <see cref="T:System.Exception" />クラスは、内部例外についての詳細を提供します。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricObjectClosedException" />指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つクラス。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (message, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para>例外の原因を説明するエラー メッセージ。</para>
        </param>
        <param name="errorCode">
          <para>例外に関連付けられているエラー コード。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.FabricObjectClosedException" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricObjectClosedException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (info, context, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="info">
          <para><see cref="T:System.Runtime.Serialization.SerializationInfo" />を含むオブジェクトがスローされた例外オブジェクト データをシリアル化します。</para>
        </param>
        <param name="context">
          <para>転送元または転送先に関するコンテキスト情報を格納する <see cref="T:System.Runtime.Serialization.StreamingContext" /> オブジェクト。 Context パラメーターは将来使用するために予約されており、null にすることができます。</para>
        </param>
        <param name="errorCode">
          <para>例外に関連付けられているエラー コード。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化<see cref="T:System.Fabric.FabricObjectClosedException" />指定のコンテキストとエラー コードを含む、シリアル化されたオブジェクトのデータからのクラスです。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (message, inner, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para>例外の原因を説明するエラー メッセージ。</para>
        </param>
        <param name="inner">
          <para>内部例外が指定されていない場合、現在の例外の原因となった例外。 <see cref="T:System.Exception" />クラスは、内部例外についての詳細を提供します。</para>
        </param>
        <param name="errorCode">
          <para>例外に関連付けられているエラー コード。</para>
        </param>
        <summary>
          <para>
            新しいインスタンスを初期化<see cref="T:System.Fabric.FabricObjectClosedException" />クラスを指定したエラー メッセージ、この例外と、指定されたエラー コードの原因となった内部例外への参照。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>