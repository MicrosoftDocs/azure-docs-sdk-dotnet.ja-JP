<Type Name="IVirtualMachine" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine">
  <TypeSignature Language="C#" Value="public interface IVirtualMachine : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineBeta, Microsoft.Azure.Management.Network.Fluent.IHasNetworkInterfaces, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachine implements class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineBeta, class Microsoft.Azure.Management.Network.Fluent.IHasNetworkInterfaces, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Compute.Fluent.IComputeManager, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachine&#xA;Implements IBeta, IGroupableResource(Of IComputeManager, VirtualMachineInner), IHasInner(Of VirtualMachineInner), IHasManager(Of IComputeManager), IHasNetworkInterfaces, IRefreshable(Of IVirtualMachine), IUpdatable(Of IUpdate), IVirtualMachineBeta" />
  <TypeSignature Language="F#" Value="type IVirtualMachine = interface&#xA;    interface IGroupableResource&lt;IComputeManager, VirtualMachineInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IComputeManager&gt;&#xA;    interface IHasInner&lt;VirtualMachineInner&gt;&#xA;    interface IRefreshable&lt;IVirtualMachine&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;&#xA;    interface IHasNetworkInterfaces&#xA;    interface IVirtualMachineBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasNetworkInterfaces</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Azure の仮想マシンの変更できないクライアント側表現。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AvailabilitySetId">
      <MemberSignature Language="C#" Value="public string AvailabilitySetId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AvailabilitySetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.AvailabilitySetId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilitySetId As String" />
      <MemberSignature Language="F#" Value="member this.AvailabilitySetId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.AvailabilitySetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この仮想マシンに関連付けられている可用性セットのリソース ID を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableSizes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize&gt; AvailableSizes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize&gt; AvailableSizes() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.AvailableSizes" />
      <MemberSignature Language="VB.NET" Value="Public Function AvailableSizes () As IEnumerable(Of IVirtualMachineSize)" />
      <MemberSignature Language="F#" Value="abstract member AvailableSizes : unit -&gt; seq&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize&gt;" Usage="iVirtualMachine.AvailableSizes " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            使用可能な仮想マシン サイズをすべてこのバーチャル マシンをサイズに変更を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>仮想マシンのサイズ。</return>
      </Docs>
    </Member>
    <Member MemberName="BootDiagnosticsStorageUri">
      <MemberSignature Language="C#" Value="public string BootDiagnosticsStorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BootDiagnosticsStorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.BootDiagnosticsStorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BootDiagnosticsStorageUri As String" />
      <MemberSignature Language="F#" Value="member this.BootDiagnosticsStorageUri : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.BootDiagnosticsStorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capture">
      <MemberSignature Language="C#" Value="public string Capture (string containerName, string vhdPrefix, bool overwriteVhd);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string Capture(string containerName, string vhdPrefix, bool overwriteVhd) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.Capture(System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function Capture (containerName As String, vhdPrefix As String, overwriteVhd As Boolean) As String" />
      <MemberSignature Language="F#" Value="abstract member Capture : string * string * bool -&gt; string" Usage="iVirtualMachine.Capture (containerName, vhdPrefix, overwriteVhd)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="vhdPrefix" Type="System.String" />
        <Parameter Name="overwriteVhd" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="containerName">キャプチャされた VHD を保存する先のコンテナー名。</param>
        <param name="vhdPrefix">キャプチャしたイメージを保持している VHD のプレフィックス。</param>
        <param name="overwriteVhd">かどうかに上書き先 VHD が存在する場合。</param>
        <summary>
            VM の仮想ハード_ディスクをコピーして、仮想マシンをキャプチャします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>このような複数の仮想マシンを作成するための JSON テンプレートです。</return>
      </Docs>
    </Member>
    <Member MemberName="CaptureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; CaptureAsync (string containerName, string vhdPrefix, bool overwriteVhd, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; CaptureAsync(string containerName, string vhdPrefix, bool overwriteVhd, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.CaptureAsync(System.String,System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CaptureAsync : string * string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iVirtualMachine.CaptureAsync (containerName, vhdPrefix, overwriteVhd, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="vhdPrefix" Type="System.String" />
        <Parameter Name="overwriteVhd" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="containerName">To be added.</param>
        <param name="vhdPrefix">To be added.</param>
        <param name="overwriteVhd">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputerName">
      <MemberSignature Language="C#" Value="public string ComputerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComputerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.ComputerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputerName As String" />
      <MemberSignature Language="F#" Value="member this.ComputerName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.ComputerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このバーチャル マシンの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertToManaged">
      <MemberSignature Language="C#" Value="public void ConvertToManaged ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ConvertToManaged() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.ConvertToManaged" />
      <MemberSignature Language="VB.NET" Value="Public Sub ConvertToManaged ()" />
      <MemberSignature Language="F#" Value="abstract member ConvertToManaged : unit -&gt; unit" Usage="iVirtualMachine.ConvertToManaged " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            変換します (移行)、ディスク バーチャル マシンで管理されていない管理対象ディスクを使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertToManagedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ConvertToManagedAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ConvertToManagedAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.ConvertToManagedAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ConvertToManagedAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachine.ConvertToManagedAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;int,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk&gt; DataDisks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;int32, class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk&gt; DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataDisks As IReadOnlyDictionary(Of Integer, IVirtualMachineDataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDisks : System.Collections.Generic.IReadOnlyDictionary&lt;int, Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.Int32,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            LUN でインデックス付けされた、この仮想マシンに関連付けられている管理対象のデータ ディスクを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deallocate">
      <MemberSignature Language="C#" Value="public void Deallocate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Deallocate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.Deallocate" />
      <MemberSignature Language="VB.NET" Value="Public Sub Deallocate ()" />
      <MemberSignature Language="F#" Value="abstract member Deallocate : unit -&gt; unit" Usage="iVirtualMachine.Deallocate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            仮想マシンをシャット ダウンし、コンピューティング リソースを解放します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeallocateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeallocateAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeallocateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.DeallocateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeallocateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachine.DeallocateAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            仮想マシンをシャット ダウンし、非同期的にコンピューティング リソースを解放します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile DiagnosticsProfile { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile DiagnosticsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.DiagnosticsProfile" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiagnosticsProfile As DiagnosticsProfile" />
      <MemberSignature Language="F#" Value="member this.DiagnosticsProfile : Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.DiagnosticsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            診断プロファイルを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskEncryption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineEncryption DiskEncryption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineEncryption DiskEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.DiskEncryption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiskEncryption As IVirtualMachineEncryption" />
      <MemberSignature Language="F#" Value="member this.DiskEncryption : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineEncryption" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.DiskEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineEncryption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            有効化、無効にしてディスクの暗号化を照会するエントリ ポイントを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Generalize">
      <MemberSignature Language="C#" Value="public void Generalize ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Generalize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.Generalize" />
      <MemberSignature Language="VB.NET" Value="Public Sub Generalize ()" />
      <MemberSignature Language="F#" Value="abstract member Generalize : unit -&gt; unit" Usage="iVirtualMachine.Generalize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            仮想マシンを一般化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeneralizeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task GeneralizeAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task GeneralizeAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.GeneralizeAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GeneralizeAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachine.GeneralizeAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            非同期的に仮想マシンを一般化します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
    <Member MemberName="GetPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress GetPrimaryPublicIPAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress GetPrimaryPublicIPAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.GetPrimaryPublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPrimaryPublicIPAddress () As IPublicIPAddress" />
      <MemberSignature Language="F#" Value="abstract member GetPrimaryPublicIPAddress : unit -&gt; Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress" Usage="iVirtualMachine.GetPrimaryPublicIPAddress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            この仮想マシンのプライマリ ネットワーク インターフェイスに関連付けられているパブリック IP アドレスを取得します。
            このメソッドは、rest API 呼び出しリソースを取得することに注意してください。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>プライマリ ネットワーク インターフェイスのパブリック IP。</return>
      </Docs>
    </Member>
    <Member MemberName="GetPrimaryPublicIPAddressId">
      <MemberSignature Language="C#" Value="public string GetPrimaryPublicIPAddressId ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetPrimaryPublicIPAddressId() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.GetPrimaryPublicIPAddressId" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPrimaryPublicIPAddressId () As String" />
      <MemberSignature Language="F#" Value="abstract member GetPrimaryPublicIPAddressId : unit -&gt; string" Usage="iVirtualMachine.GetPrimaryPublicIPAddressId " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>パブリック IP アドレスのリソース ID は、この仮想マシンのプライマリ ネットワーク インターフェイスに関連付けられています。</return>
      </Docs>
    </Member>
    <Member MemberName="InstanceView">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView InstanceView { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView InstanceView" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.InstanceView" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceView As VirtualMachineInstanceView" />
      <MemberSignature Language="F#" Value="member this.InstanceView : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.InstanceView" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            仮想マシン インスタンス ビューを取得します。
            インスタンス ビューは、以降の取得を使用してにキャッシュする<code>instanceView</code>です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBootDiagnosticsEnabled">
      <MemberSignature Language="C#" Value="public bool IsBootDiagnosticsEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBootDiagnosticsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.IsBootDiagnosticsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBootDiagnosticsEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBootDiagnosticsEnabled : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.IsBootDiagnosticsEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsManagedDiskEnabled">
      <MemberSignature Language="C#" Value="public bool IsManagedDiskEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsManagedDiskEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.IsManagedDiskEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsManagedDiskEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsManagedDiskEnabled : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.IsManagedDiskEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            管理対象ディスクがバーチャル マシンのディスク (OS、データ) を使用する場合は true を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.LicenseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            LicenseType 値を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListExtensions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtension&gt; ListExtensions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtension&gt; ListExtensions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.ListExtensions" />
      <MemberSignature Language="VB.NET" Value="Public Function ListExtensions () As IReadOnlyDictionary(Of String, IVirtualMachineExtension)" />
      <MemberSignature Language="F#" Value="abstract member ListExtensions : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtension&gt;" Usage="iVirtualMachine.ListExtensions " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtension&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>仮想マシンにアタッチされている拡張機能です。</return>
      </Docs>
    </Member>
    <Member MemberName="ListExtensionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtension&gt;&gt; ListExtensionsAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtension&gt;&gt; ListExtensionsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.ListExtensionsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListExtensionsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtension&gt;&gt;" Usage="iVirtualMachine.ListExtensionsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtension&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskCachingType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes OSDiskCachingType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes OSDiskCachingType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.OSDiskCachingType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskCachingType As CachingTypes" />
      <MemberSignature Language="F#" Value="member this.OSDiskCachingType : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.OSDiskCachingType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            キャッシュの種類をオペレーティング システム ディスクを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskId">
      <MemberSignature Language="C#" Value="public string OSDiskId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OSDiskId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.OSDiskId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskId As String" />
      <MemberSignature Language="F#" Value="member this.OSDiskId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.OSDiskId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            OS ディスクをバックアップする管理対象ディスクのリソース ID を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskSize">
      <MemberSignature Language="C#" Value="public int OSDiskSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 OSDiskSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.OSDiskSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskSize As Integer" />
      <MemberSignature Language="F#" Value="member this.OSDiskSize : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.OSDiskSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            オペレーティング システム ディスクのサイズを GB 単位を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskStorageAccountType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt; OSDiskStorageAccountType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt; OSDiskStorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.OSDiskStorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskStorageAccountType As Nullable(Of StorageAccountTypes)" />
      <MemberSignature Language="F#" Value="member this.OSDiskStorageAccountType : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.OSDiskStorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            OS ディスクのバックアップを作成、管理対象ディスクのストレージ アカウントの種類を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile OSProfile { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile OSProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.OSProfile" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSProfile As OSProfile" />
      <MemberSignature Language="F#" Value="member this.OSProfile : Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.OSProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            オペレーティング システム プロファイルを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OSType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OSType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.OSType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSType As OperatingSystemTypes" />
      <MemberSignature Language="F#" Value="member this.OSType : Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.OSType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このバーチャル マシンのオペレーティング システムを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSUnmanagedDiskVhdUri">
      <MemberSignature Language="C#" Value="public string OSUnmanagedDiskVhdUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OSUnmanagedDiskVhdUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.OSUnmanagedDiskVhdUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSUnmanagedDiskVhdUri As String" />
      <MemberSignature Language="F#" Value="member this.OSUnmanagedDiskVhdUri : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.OSUnmanagedDiskVhdUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この仮想マシンのオペレーティング システム ディスクをバックアップした VHD ファイルへの URI を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Plan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.Plan Plan { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.Plan Plan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.Plan" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Plan As Plan" />
      <MemberSignature Language="F#" Value="member this.Plan : Microsoft.Azure.Management.Compute.Fluent.Models.Plan" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.Plan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.Plan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プランの値を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOff">
      <MemberSignature Language="C#" Value="public void PowerOff ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void PowerOff() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.PowerOff" />
      <MemberSignature Language="VB.NET" Value="Public Sub PowerOff ()" />
      <MemberSignature Language="F#" Value="abstract member PowerOff : unit -&gt; unit" Usage="iVirtualMachine.PowerOff " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            電源、仮想マシン (停止) をオフにします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOffAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PowerOffAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PowerOffAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.PowerOffAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PowerOffAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachine.PowerOffAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            電源がオフ (停止) 仮想マシンに非同期的にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
    <Member MemberName="PowerState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.PowerState PowerState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.PowerState PowerState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.PowerState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PowerState As PowerState" />
      <MemberSignature Language="F#" Value="member this.PowerState : Microsoft.Azure.Management.Compute.Fluent.PowerState" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.PowerState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.PowerState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            仮想マシンの電源の状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ProvisioningState 値を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Redeploy">
      <MemberSignature Language="C#" Value="public void Redeploy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Redeploy() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.Redeploy" />
      <MemberSignature Language="VB.NET" Value="Public Sub Redeploy ()" />
      <MemberSignature Language="F#" Value="abstract member Redeploy : unit -&gt; unit" Usage="iVirtualMachine.Redeploy " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            仮想マシンを再デプロイします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedeployAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RedeployAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RedeployAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.RedeployAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RedeployAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachine.RedeployAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            非同期的に仮想マシンを再配置されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
    <Member MemberName="RefreshInstanceView">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView RefreshInstanceView ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView RefreshInstanceView() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.RefreshInstanceView" />
      <MemberSignature Language="VB.NET" Value="Public Function RefreshInstanceView () As VirtualMachineInstanceView" />
      <MemberSignature Language="F#" Value="abstract member RefreshInstanceView : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView" Usage="iVirtualMachine.RefreshInstanceView " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Azure と同期する仮想マシン インスタンス ビューを更新します。
            インスタンス ビューは、以降の取得を使用してにキャッシュする<code>instanceView</code>です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新のインスタンス ビューです。</return>
      </Docs>
    </Member>
    <Member MemberName="RefreshInstanceViewAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView&gt; RefreshInstanceViewAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView&gt; RefreshInstanceViewAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.RefreshInstanceViewAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshInstanceViewAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView&gt;" Usage="iVirtualMachine.RefreshInstanceViewAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Azure と同期する仮想マシン インスタンス ビューを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
        <return>仮想マシンのインスタンス ビューを出力する observable。</return>
      </Docs>
    </Member>
    <Member MemberName="Restart">
      <MemberSignature Language="C#" Value="public void Restart ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Restart() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.Restart" />
      <MemberSignature Language="VB.NET" Value="Public Sub Restart ()" />
      <MemberSignature Language="F#" Value="abstract member Restart : unit -&gt; unit" Usage="iVirtualMachine.Restart " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            仮想マシンを再起動します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestartAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestartAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.RestartAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestartAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachine.RestartAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            非同期的に仮想マシンを再起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes Size { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.Size" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Size As VirtualMachineSizeTypes" />
      <MemberSignature Language="F#" Value="member this.Size : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.Size" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            仮想マシンのサイズを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public void Start ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Start() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.Start" />
      <MemberSignature Language="VB.NET" Value="Public Sub Start ()" />
      <MemberSignature Language="F#" Value="abstract member Start : unit -&gt; unit" Usage="iVirtualMachine.Start " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            仮想マシンを起動します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StartAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.StartAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachine.StartAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            仮想マシンを非同期的に起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
    <Member MemberName="StorageProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile StorageProfile { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile StorageProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.StorageProfile" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageProfile As StorageProfile" />
      <MemberSignature Language="F#" Value="member this.StorageProfile : Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.StorageProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            返します。 Azure の仮想マシンの記憶域のプロファイルを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnmanagedDataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;int,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk&gt; UnmanagedDataDisks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;int32, class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk&gt; UnmanagedDataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.UnmanagedDataDisks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnmanagedDataDisks As IReadOnlyDictionary(Of Integer, IVirtualMachineUnmanagedDataDisk)" />
      <MemberSignature Language="F#" Value="member this.UnmanagedDataDisks : System.Collections.Generic.IReadOnlyDictionary&lt;int, Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.UnmanagedDataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.Int32,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            LUN の数字のインデックスをこの仮想マシンに関連付けられたアンマネージ データ ディスクを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VMId">
      <MemberSignature Language="C#" Value="public string VMId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VMId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.VMId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VMId As String" />
      <MemberSignature Language="F#" Value="member this.VMId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine.VMId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            仮想マシンの一意の ID を取得します
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>