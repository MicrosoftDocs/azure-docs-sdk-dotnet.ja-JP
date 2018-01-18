<Type Name="IWithFloatingIP&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.HasFloatingIP.Definition.IWithFloatingIP&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithFloatingIP&lt;ReturnT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFloatingIP`1&lt;ReturnT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.HasFloatingIP.Definition.IWithFloatingIP`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFloatingIP(Of ReturnT)" />
  <TypeSignature Language="F#" Value="type IWithFloatingIP&lt;'ReturnT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ReturnT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ReturnT"><span data-ttu-id="e2fcc-101">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="e2fcc-101">The next stage of the definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="e2fcc-102">フローティング IP サポートを制御できるように定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="e2fcc-102">The stage of a definition allowing to control floating IP support.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithFloatingIP">
      <MemberSignature Language="C#" Value="public ReturnT WithFloatingIP (bool enabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithFloatingIP(bool enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasFloatingIP.Definition.IWithFloatingIP`1.WithFloatingIP(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFloatingIP (enabled As Boolean) As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithFloatingIP : bool -&gt; 'ReturnT" Usage="iWithFloatingIP.WithFloatingIP enabled" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="enabled"><span data-ttu-id="e2fcc-103">フローティング IP を有効にする場合は true。</span><span class="sxs-lookup"><span data-stu-id="e2fcc-103">True if floating IP should be enabled.</span></span></param>
        <summary>
            <span data-ttu-id="e2fcc-104">フローティング IP 有効化を設定します。</span><span class="sxs-lookup"><span data-stu-id="e2fcc-104">Sets the floating IP enablement.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e2fcc-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="e2fcc-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithFloatingIPDisabled">
      <MemberSignature Language="C#" Value="public ReturnT WithFloatingIPDisabled ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithFloatingIPDisabled() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasFloatingIP.Definition.IWithFloatingIP`1.WithFloatingIPDisabled" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFloatingIPDisabled () As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithFloatingIPDisabled : unit -&gt; 'ReturnT" Usage="iWithFloatingIP.WithFloatingIPDisabled " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e2fcc-106">浮動小数点 IP サポートを無効にします。</span><span class="sxs-lookup"><span data-stu-id="e2fcc-106">Disables floating IP support.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e2fcc-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="e2fcc-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithFloatingIPEnabled">
      <MemberSignature Language="C#" Value="public ReturnT WithFloatingIPEnabled ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithFloatingIPEnabled() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasFloatingIP.Definition.IWithFloatingIP`1.WithFloatingIPEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFloatingIPEnabled () As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithFloatingIPEnabled : unit -&gt; 'ReturnT" Usage="iWithFloatingIP.WithFloatingIPEnabled " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e2fcc-108">浮動小数点 IP サポートを有効にします。</span><span class="sxs-lookup"><span data-stu-id="e2fcc-108">Enables floating IP support.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e2fcc-109">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="e2fcc-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>