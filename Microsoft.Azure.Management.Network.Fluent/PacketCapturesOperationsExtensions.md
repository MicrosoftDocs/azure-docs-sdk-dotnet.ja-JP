<Type Name="PacketCapturesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PacketCapturesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PacketCapturesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PacketCapturesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PacketCapturesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            PacketCapturesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt; BeginCreateAsync (this Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt; BeginCreateAsync(class Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, networkWatcherName, packetCaptureName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions/&lt;BeginCreateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="packetCaptureName">
            パケット キャプチャ セッションの名前。
            </param>
        <param name="parameters">
            作成するパケットを定義するパラメーターは、操作をキャプチャします。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成し、指定した VM 上のパケット キャプチャを開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, networkWatcherName, packetCaptureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="packetCaptureName">
            パケット キャプチャ セッションの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたパケットのキャプチャ セッションを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureQueryStatusResultInner&gt; BeginGetStatusAsync (this Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureQueryStatusResultInner&gt; BeginGetStatusAsync(class Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.BeginGetStatusAsync(Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetStatusAsync : Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureQueryStatusResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.BeginGetStatusAsync (operations, resourceGroupName, networkWatcherName, packetCaptureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions/&lt;BeginGetStatusAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureQueryStatusResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャー リソースの名前。
            </param>
        <param name="packetCaptureName">
            パケット キャプチャ セッションに与えられた名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            実行中のパケット キャプチャ セッションの状態を照会します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStopAsync (this Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStopAsync(class Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.BeginStopAsync(Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStopAsync : Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.BeginStopAsync (operations, resourceGroupName, networkWatcherName, packetCaptureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions/&lt;BeginStopAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="packetCaptureName">
            パケット キャプチャ セッションの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            停止した場合に指定されたパケットは、セッションをキャプチャします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt; CreateAsync (this Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt; CreateAsync(class Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.CreateAsync (operations, resourceGroupName, networkWatcherName, packetCaptureName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions/&lt;CreateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="packetCaptureName">
            パケット キャプチャ セッションの名前。
            </param>
        <param name="parameters">
            作成するパケットを定義するパラメーターは、操作をキャプチャします。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成し、指定した VM 上のパケット キャプチャを開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.DeleteAsync (operations, resourceGroupName, networkWatcherName, packetCaptureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="packetCaptureName">
            パケット キャプチャ セッションの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたパケットのキャプチャ セッションを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.GetAsync (operations, resourceGroupName, networkWatcherName, packetCaptureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="packetCaptureName">
            パケット キャプチャ セッションの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            名前で、パケット キャプチャ セッションを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureQueryStatusResultInner&gt; GetStatusAsync (this Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureQueryStatusResultInner&gt; GetStatusAsync(class Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.GetStatusAsync(Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStatusAsync : Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureQueryStatusResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.GetStatusAsync (operations, resourceGroupName, networkWatcherName, packetCaptureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions/&lt;GetStatusAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureQueryStatusResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャー リソースの名前。
            </param>
        <param name="packetCaptureName">
            パケット キャプチャ セッションに与えられた名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            実行中のパケット キャプチャ セッションの状態を照会します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.ListAsync (operations, resourceGroupName, networkWatcherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャー リソースの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたリソース グループ内のすべてのパケット キャプチャ セッションの一覧を示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StopAsync (this Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StopAsync(class Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations operations, string resourceGroupName, string networkWatcherName, string packetCaptureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.StopAsync(Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions.StopAsync (operations, resourceGroupName, networkWatcherName, packetCaptureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PacketCapturesOperationsExtensions/&lt;StopAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPacketCapturesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkWatcherName" Type="System.String" />
        <Parameter Name="packetCaptureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkWatcherName">
            ネットワーク ウォッチャーの名前。
            </param>
        <param name="packetCaptureName">
            パケット キャプチャ セッションの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            停止した場合に指定されたパケットは、セッションをキャプチャします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>