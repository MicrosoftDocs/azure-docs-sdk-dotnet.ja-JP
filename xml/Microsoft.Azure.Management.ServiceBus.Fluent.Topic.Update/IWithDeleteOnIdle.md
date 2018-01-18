<Type Name="IWithDeleteOnIdle" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithDeleteOnIdle">
  <TypeSignature Language="C#" Value="public interface IWithDeleteOnIdle" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDeleteOnIdle" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithDeleteOnIdle" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDeleteOnIdle" />
  <TypeSignature Language="F#" Value="type IWithDeleteOnIdle = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7af1f-101">自動を定義できるようにトピック定義のステージでは、動作を削除します。</span><span class="sxs-lookup"><span data-stu-id="7af1f-101">The stage of the topic definition allowing to define auto delete behaviour.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDeleteOnIdleDurationInMinutes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithDeleteOnIdleDurationInMinutes (int durationInMinutes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithDeleteOnIdleDurationInMinutes(int32 durationInMinutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithDeleteOnIdle.WithDeleteOnIdleDurationInMinutes(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDeleteOnIdleDurationInMinutes (durationInMinutes As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDeleteOnIdleDurationInMinutes : int -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate" Usage="iWithDeleteOnIdle.WithDeleteOnIdleDurationInMinutes durationInMinutes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="durationInMinutes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="durationInMinutes"><span data-ttu-id="7af1f-102">アイドル状態の期間 (分) です。</span><span class="sxs-lookup"><span data-stu-id="7af1f-102">Idle duration in minutes.</span></span></param>
        <summary>
            <span data-ttu-id="7af1f-103">トピックは自動的に削除するまでのアイドル間隔です。</span><span class="sxs-lookup"><span data-stu-id="7af1f-103">The idle interval after which the topic is automatically deleted.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7af1f-104">トピックの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="7af1f-104">The next stage of topic update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>