<Type Name="IWithOSSettings" FullName="Microsoft.Azure.Management.Compute.Fluent.Snapshot.Update.IWithOSSettings">
  <TypeSignature Language="C#" Value="public interface IWithOSSettings" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithOSSettings" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Update.IWithOSSettings" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithOSSettings" />
  <TypeSignature Language="F#" Value="type IWithOSSettings = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c271c-101">OS の設定を指定できるように管理対象のスナップショットの更新の段階です。</span><span class="sxs-lookup"><span data-stu-id="c271c-101">The stage of the managed snapshot update allowing to specify OS settings.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithOSType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Update.IUpdate WithOSType (Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes osType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Update.IUpdate WithOSType(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes osType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Update.IWithOSSettings.WithOSType(Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSType (osType As OperatingSystemTypes) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithOSType : Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Update.IUpdate" Usage="iWithOSSettings.WithOSType osType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="osType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" />
      </Parameters>
      <Docs>
        <param name="osType"><span data-ttu-id="c271c-102">オペレーティング システムの種類。</span><span class="sxs-lookup"><span data-stu-id="c271c-102">Operating system type.</span></span></param>
        <summary>
            <span data-ttu-id="c271c-103">オペレーティング システムの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="c271c-103">Specifies the operating system type.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c271c-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c271c-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>