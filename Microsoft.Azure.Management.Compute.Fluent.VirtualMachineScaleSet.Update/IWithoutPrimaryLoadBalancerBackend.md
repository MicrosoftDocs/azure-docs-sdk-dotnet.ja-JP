<Type Name="IWithoutPrimaryLoadBalancerBackend" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerBackend">
  <TypeSignature Language="C#" Value="public interface IWithoutPrimaryLoadBalancerBackend" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithoutPrimaryLoadBalancerBackend" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerBackend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithoutPrimaryLoadBalancerBackend" />
  <TypeSignature Language="F#" Value="type IWithoutPrimaryLoadBalancerBackend = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            仮想マシンのスケールのステージでは、プライマリ ネットワーク インターフェイスの構成とロード バランサーのバックエンドの間の関連付けの削除を許可する更新を設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutPrimaryInternalLoadBalancerBackends">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternalLoadBalancerBackends (params string[] backendNames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternalLoadBalancerBackends(string[] backendNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerBackend.WithoutPrimaryInternalLoadBalancerBackends(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryInternalLoadBalancerBackends (ParamArray backendNames As String()) As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryInternalLoadBalancerBackends : string[] -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithoutPrimaryLoadBalancerBackend.WithoutPrimaryInternalLoadBalancerBackends backendNames" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backendNames" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="backendNames">既存のバックエンド名。</param>
        <summary>
            プライマリ ネットワーク インターフェイスの構成と指定された内部ロード バランサーのバックエンドの間の関連付けを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPrimaryInternetFacingLoadBalancerBackends">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternetFacingLoadBalancerBackends (params string[] backendNames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternetFacingLoadBalancerBackends(string[] backendNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerBackend.WithoutPrimaryInternetFacingLoadBalancerBackends(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryInternetFacingLoadBalancerBackends (ParamArray backendNames As String()) As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryInternetFacingLoadBalancerBackends : string[] -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithoutPrimaryLoadBalancerBackend.WithoutPrimaryInternetFacingLoadBalancerBackends backendNames" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backendNames" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="backendNames">既存のバックエンド名。</param>
        <summary>
            プライマリ ネットワーク インターフェイスの構成と、インターネットに接続するロード バランサーの指定されたバックエンドの間の関連付けを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>