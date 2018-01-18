<Type Name="AzureActiveDirectoryTokenProvider" FullName="Microsoft.Azure.ServiceBus.Primitives.AzureActiveDirectoryTokenProvider">
  <TypeSignature Language="C#" Value="public class AzureActiveDirectoryTokenProvider : Microsoft.Azure.ServiceBus.Primitives.TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureActiveDirectoryTokenProvider extends Microsoft.Azure.ServiceBus.Primitives.TokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Primitives.AzureActiveDirectoryTokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureActiveDirectoryTokenProvider&#xA;Inherits TokenProvider" />
  <TypeSignature Language="F#" Value="type AzureActiveDirectoryTokenProvider = class&#xA;    inherit TokenProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7865a-101">Service Bus の Azure Active Directory のトークン プロバイダーを表します。</span><span class="sxs-lookup"><span data-stu-id="7865a-101">Represents the Azure Active Directory token provider for the Service Bus.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetTokenAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Primitives.SecurityToken&gt; GetTokenAsync (string appliesTo, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Primitives.SecurityToken&gt; GetTokenAsync(string appliesTo, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.AzureActiveDirectoryTokenProvider.GetTokenAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetTokenAsync (appliesTo As String, timeout As TimeSpan) As Task(Of SecurityToken)" />
      <MemberSignature Language="F#" Value="override this.GetTokenAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Primitives.SecurityToken&gt;" Usage="azureActiveDirectoryTokenProvider.GetTokenAsync (appliesTo, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Primitives.AzureActiveDirectoryTokenProvider/&lt;GetTokenAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Primitives.SecurityToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="7865a-102">アクセス トークンが適用される URI</span><span class="sxs-lookup"><span data-stu-id="7865a-102">The URI which the access token applies to</span></span></param>
        <param name="timeout"><span data-ttu-id="7865a-103">セキュリティ トークンを取得するメッセージのタイムアウト値を指定する時間間隔</span><span class="sxs-lookup"><span data-stu-id="7865a-103">The time span that specifies the timeout value for the message that gets the security token</span></span></param>
        <summary>
            <span data-ttu-id="7865a-104">取得、<see cref="T:Microsoft.Azure.ServiceBus.Primitives.SecurityToken" />指定された対象ユーザーと期間。</span><span class="sxs-lookup"><span data-stu-id="7865a-104">Gets a <see cref="T:Microsoft.Azure.ServiceBus.Primitives.SecurityToken" /> for the given audience and duration.</span></span>
            </summary>
        <returns>
          <see cref="T:Microsoft.Azure.ServiceBus.Primitives.SecurityToken" />
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>