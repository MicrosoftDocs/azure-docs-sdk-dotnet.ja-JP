<Type Name="HybridConnectionStream" FullName="Microsoft.Azure.Relay.HybridConnectionStream">
  <TypeSignature Language="C#" Value="public abstract class HybridConnectionStream : System.IO.Stream" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit HybridConnectionStream extends System.IO.Stream" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.HybridConnectionStream" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class HybridConnectionStream&#xA;Inherits Stream" />
  <TypeSignature Language="F#" Value="type HybridConnectionStream = class&#xA;    inherit Stream" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IO.Stream</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            接続されている HybridConnection を表すストリーム。  発生しているその他のストリームの追加すると、この接続の相手側に通知するためのシャット ダウン メソッドのシャット ダウンするように使用します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionStream.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionStream.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionStream/&lt;CloseAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">観察するキャンセル トークン。</param>
        <summary>
            これを閉じます<see cref="T:Microsoft.Azure.Relay.HybridConnectionStream" />インスタンスを使用して非同期的に、<see cref="T:System.Threading.CancellationToken" />です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected override void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionStream.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.Dispose : bool -&gt; unit" Usage="hybridConnectionStream.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">マネージ リソースとアンマネージ リソースの両方を解放する場合は true、アンマネージ リソースだけを解放する場合は false。</param>
        <summary>
            これを閉じます<see cref="T:Microsoft.Azure.Relay.HybridConnectionStream" />インスタンス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task OnCloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionStream.OnCloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionStream.OnCloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">観察するキャンセル トークン。</param>
        <summary>
            派生クラスでは、このメソッドにクローズ ロジックを実装します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnShutdownAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task OnShutdownAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnShutdownAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionStream.OnShutdownAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnShutdownAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionStream.OnShutdownAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">観察するキャンセル トークン。</param>
        <summary>
            派生クラスでは、この方法でシャット ダウン ロジックを実装します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Shutdown">
      <MemberSignature Language="C#" Value="public virtual void Shutdown ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Shutdown() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionStream.Shutdown" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Shutdown ()" />
      <MemberSignature Language="F#" Value="abstract member Shutdown : unit -&gt; unit&#xA;override this.Shutdown : unit -&gt; unit" Usage="hybridConnectionStream.Shutdown " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            このを介して送信することをシャット ダウンして正常な終了処理を開始する<see cref="T:Microsoft.Azure.Relay.HybridConnectionStream" />です。 切断するにはクリーンにおよび非同期的にシャット ダウンを呼び出して、待ってから、読み取り/ReadAsync 0 バイトの読み取り、更新が完了し、最後に呼び出して、Stream.Close() です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShutdownAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ShutdownAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ShutdownAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionStream.ShutdownAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ShutdownAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionStream.ShutdownAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionStream/&lt;ShutdownAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">観察するキャンセル トークン。</param>
        <summary>
            このを介して送信することをシャット ダウンして正常な終了処理を開始する<see cref="T:Microsoft.Azure.Relay.HybridConnectionStream" />です。 切断するにはクリーンにおよび非同期的に呼び出す ShutdownAsync 待ってから、読み取り/ReadAsync 0 バイトの読み取り、更新が完了し、最後に呼び出して、Stream.CloseAsync();
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionStream.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="hybridConnectionStream.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在のオブジェクトを表す文字列を返します。  エンド ツー エンドの相関関係の TrackingId が含まれます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Relay.WriteMode WriteMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Relay.WriteMode WriteMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionStream.WriteMode" />
      <MemberSignature Language="VB.NET" Value="Public Property WriteMode As WriteMode" />
      <MemberSignature Language="F#" Value="member this.WriteMode : Microsoft.Azure.Relay.WriteMode with get, set" Usage="Microsoft.Azure.Relay.HybridConnectionStream.WriteMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Relay.WriteMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            設定またはこのストリームの WriteMode を取得します。 既定値は WriteMode.Binary
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>