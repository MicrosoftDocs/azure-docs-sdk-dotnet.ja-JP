<Type Name="OnTaskFailure" FullName="Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure">
  <TypeSignature Language="C#" Value="public enum OnTaskFailure" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed OnTaskFailure extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure" />
  <TypeSignature Language="VB.NET" Value="Public Enum OnTaskFailure" />
  <TypeSignature Language="F#" Value="type OnTaskFailure = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c5611-101">OnTaskFailure の値を定義します。</span><span class="sxs-lookup"><span data-stu-id="c5611-101">Defines values for OnTaskFailure.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NoAction">
      <MemberSignature Language="C#" Value="NoAction" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure NoAction = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure.NoAction" />
      <MemberSignature Language="VB.NET" Value="NoAction" />
      <MemberSignature Language="F#" Value="NoAction = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure.NoAction" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="noaction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="c5611-102">何もしません。</span><span class="sxs-lookup"><span data-stu-id="c5611-102">Do nothing.</span></span> <span data-ttu-id="c5611-103">ジョブでは、終了または他のいくつかの方法で無効になっている場合を除きが消えない。</span><span class="sxs-lookup"><span data-stu-id="c5611-103">The job remains active unless terminated or disabled by some other means.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="PerformExitOptionsJobAction">
      <MemberSignature Language="C#" Value="PerformExitOptionsJobAction" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure PerformExitOptionsJobAction = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure.PerformExitOptionsJobAction" />
      <MemberSignature Language="VB.NET" Value="PerformExitOptionsJobAction" />
      <MemberSignature Language="F#" Value="PerformExitOptionsJobAction = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure.PerformExitOptionsJobAction" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="performexitoptionsjobaction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="c5611-104">タスクの exitConditions コレクション内のタスクの終了条件に関連付けられているアクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="c5611-104">Take the action associated with the task exit condition in the task's exitConditions collection.</span></span> <span data-ttu-id="c5611-105">(このまだあります何も行われているタスクが指定される場合。)</span><span class="sxs-lookup"><span data-stu-id="c5611-105">(This may still result in no action being taken, if that is what the task specifies.)</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>