<Type Name="IHardwareComponentGroupsOperations" FullName="Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations">
  <TypeSignature Language="C#" Value="public interface IHardwareComponentGroupsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IHardwareComponentGroupsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IHardwareComponentGroupsOperations" />
  <TypeSignature Language="F#" Value="type IHardwareComponentGroupsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            HardwareComponentGroupsOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginChangeControllerPowerStateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginChangeControllerPowerStateWithHttpMessagesAsync (string deviceName, string hardwareComponentGroupName, Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginChangeControllerPowerStateWithHttpMessagesAsync(string deviceName, string hardwareComponentGroupName, class Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations.BeginChangeControllerPowerStateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginChangeControllerPowerStateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iHardwareComponentGroupsOperations.BeginChangeControllerPowerStateWithHttpMessagesAsync (deviceName, hardwareComponentGroupName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="hardwareComponentGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            デバイス名
            </param>
        <param name="hardwareComponentGroupName">
            ハードウェア コンポーネント グループの名前。
            </param>
        <param name="parameters">
            コント ローラーの電源状態では、要求を変更します。
            </param>
        <param name="resourceGroupName">
            リソース グループ名
            </param>
        <param name="managerName">
            管理者名
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            コント ローラーの電源の状態を変更します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ChangeControllerPowerStateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ChangeControllerPowerStateWithHttpMessagesAsync (string deviceName, string hardwareComponentGroupName, Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ChangeControllerPowerStateWithHttpMessagesAsync(string deviceName, string hardwareComponentGroupName, class Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations.ChangeControllerPowerStateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeControllerPowerStateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iHardwareComponentGroupsOperations.ChangeControllerPowerStateWithHttpMessagesAsync (deviceName, hardwareComponentGroupName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="hardwareComponentGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            デバイス名
            </param>
        <param name="hardwareComponentGroupName">
            ハードウェア コンポーネント グループの名前。
            </param>
        <param name="parameters">
            コント ローラーの電源状態では、要求を変更します。
            </param>
        <param name="resourceGroupName">
            リソース グループ名
            </param>
        <param name="managerName">
            管理者名
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            コント ローラーの電源の状態を変更します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;&gt;&gt; ListByDeviceWithHttpMessagesAsync (string deviceName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;&gt;&gt; ListByDeviceWithHttpMessagesAsync(string deviceName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations.ListByDeviceWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDeviceWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;&gt;&gt;" Usage="iHardwareComponentGroupsOperations.ListByDeviceWithHttpMessagesAsync (deviceName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            デバイス名
            </param>
        <param name="resourceGroupName">
            リソース グループ名
            </param>
        <param name="managerName">
            管理者名
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            デバイス レベルでのハードウェア コンポーネント グループを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>