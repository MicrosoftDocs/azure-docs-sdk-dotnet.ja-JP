<Type Name="IWithDeleteOnIdle" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithDeleteOnIdle">
  <TypeSignature Language="C#" Value="public interface IWithDeleteOnIdle" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDeleteOnIdle" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithDeleteOnIdle" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDeleteOnIdle" />
  <TypeSignature Language="F#" Value="type IWithDeleteOnIdle = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ebbe9-101">自動の定義を許可するサブスクリプション定義のステージでは、動作を削除します。</span><span class="sxs-lookup"><span data-stu-id="ebbe9-101">The stage of the subscription definition allowing to define auto delete behaviour.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDeleteOnIdleDurationInMinutes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate WithDeleteOnIdleDurationInMinutes (int durationInMinutes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate WithDeleteOnIdleDurationInMinutes(int32 durationInMinutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithDeleteOnIdle.WithDeleteOnIdleDurationInMinutes(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDeleteOnIdleDurationInMinutes (durationInMinutes As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDeleteOnIdleDurationInMinutes : int -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate" Usage="iWithDeleteOnIdle.WithDeleteOnIdleDurationInMinutes durationInMinutes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="durationInMinutes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="durationInMinutes"><span data-ttu-id="ebbe9-102">アイドル状態の期間 (分) です。</span><span class="sxs-lookup"><span data-stu-id="ebbe9-102">Idle duration in minutes.</span></span></param>
        <summary>
            <span data-ttu-id="ebbe9-103">その後、サブスクリプションは自動的に削除アイドル状態の間隔です。</span><span class="sxs-lookup"><span data-stu-id="ebbe9-103">The idle interval after which the subscription is automatically deleted.</span></span>
            <span data-ttu-id="ebbe9-104">注: は明示的にオーバーライドしない限り、アイドル状態の期間で delete を既定値は無限 (TimeSpan.Max)。</span><span class="sxs-lookup"><span data-stu-id="ebbe9-104">Note: unless it is explicitly overridden the default delete on idle duration is infinite (TimeSpan.Max).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ebbe9-105">サブスクリプション定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ebbe9-105">The next stage of subscription definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>