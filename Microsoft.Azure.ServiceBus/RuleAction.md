<Type Name="RuleAction" FullName="Microsoft.Azure.ServiceBus.RuleAction">
  <TypeSignature Language="C#" Value="public abstract class RuleAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit RuleAction extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.RuleAction" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class RuleAction" />
  <TypeSignature Language="F#" Value="type RuleAction = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2b096-101">フィルター式が一致するメッセージの変換で許可されているフィルター操作を表します。</span><span class="sxs-lookup"><span data-stu-id="2b096-101">Represents the filter actions which are allowed for the transformation of a message that have been matched by a filter expression.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="2b096-102">フィルター式と一致しているメッセージの変換のためのフィルタ操作を許可します。</span><span class="sxs-lookup"><span data-stu-id="2b096-102">Filter actions allow for the transformation of a message that have been matched by a filter expression.</span></span>
            <span data-ttu-id="2b096-103">フィルター操作の一般的なユース ケースは、追加またはメッセージの相関 ID に基づくグループ ID の割り当てなど、メッセージに関連付けられているプロパティを更新することです。</span><span class="sxs-lookup"><span data-stu-id="2b096-103">The typical use case for filter actions is to append or update the properties that are attached to a message, for example assigning a group ID based on the correlation ID of a message.</span></span>
            </remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.SqlRuleAction" />
  </Docs>
  <Members />
</Type>