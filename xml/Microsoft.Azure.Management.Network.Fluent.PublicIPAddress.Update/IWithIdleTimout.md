<Type Name="IWithIdleTimout" FullName="Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithIdleTimout">
  <TypeSignature Language="C#" Value="public interface IWithIdleTimout" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIdleTimout" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithIdleTimout" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIdleTimout" />
  <TypeSignature Language="F#" Value="type IWithIdleTimout = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="83cd5-101">パブリック IP アドレスは、アイドル タイムアウトを変更する許可を更新します。</span><span class="sxs-lookup"><span data-stu-id="83cd5-101">A public IP address update allowing the idle timeout to be changed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithIdleTimeoutInMinutes (int minutes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithIdleTimeoutInMinutes(int32 minutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithIdleTimout.WithIdleTimeoutInMinutes(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIdleTimeoutInMinutes (minutes As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithIdleTimeoutInMinutes : int -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate" Usage="iWithIdleTimout.WithIdleTimeoutInMinutes minutes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="minutes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="minutes"><span data-ttu-id="83cd5-102">分のタイムアウト時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="83cd5-102">The length of the time out in minutes.</span></span></param>
        <summary>
            <span data-ttu-id="83cd5-103">タイムアウト (分) のアイドル状態の接続を指定します。</span><span class="sxs-lookup"><span data-stu-id="83cd5-103">Specifies the timeout (in minutes) for an idle connection.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="83cd5-104">リソースの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="83cd5-104">The next stage of the resource update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>