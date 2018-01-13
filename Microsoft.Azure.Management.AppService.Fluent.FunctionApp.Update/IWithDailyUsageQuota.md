<Type Name="IWithDailyUsageQuota" FullName="Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithDailyUsageQuota">
  <TypeSignature Language="C#" Value="public interface IWithDailyUsageQuota" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDailyUsageQuota" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithDailyUsageQuota" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDailyUsageQuota" />
  <TypeSignature Language="F#" Value="type IWithDailyUsageQuota = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="628eb-101">関数アプリ定義毎日使用量クォータを指定するを許可します。</span><span class="sxs-lookup"><span data-stu-id="628eb-101">A function app definition allowing daily usage quota to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDailyUsageQuota">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithDailyUsageQuota (int quota);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithDailyUsageQuota(int32 quota) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithDailyUsageQuota.WithDailyUsageQuota(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDailyUsageQuota (quota As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDailyUsageQuota : int -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate" Usage="iWithDailyUsageQuota.WithDailyUsageQuota quota" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="quota" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="quota"><span data-ttu-id="628eb-102">使用状況クォータを日単位です。</span><span class="sxs-lookup"><span data-stu-id="628eb-102">The daily usage quota.</span></span></param>
        <summary>
            <span data-ttu-id="628eb-103">1 日の使用状況データの上限を指定します。</span><span class="sxs-lookup"><span data-stu-id="628eb-103">Specifies the daily usage data cap.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="628eb-104">関数アプリの更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="628eb-104">The next stage of the function app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutDailyUsageQuota">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithoutDailyUsageQuota ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithoutDailyUsageQuota() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithDailyUsageQuota.WithoutDailyUsageQuota" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutDailyUsageQuota () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutDailyUsageQuota : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate" Usage="iWithDailyUsageQuota.WithoutDailyUsageQuota " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="628eb-105">1 日の使用状況データの上限を指定します。</span><span class="sxs-lookup"><span data-stu-id="628eb-105">Specifies the daily usage data cap.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="628eb-106">関数アプリの更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="628eb-106">The next stage of the function app update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>