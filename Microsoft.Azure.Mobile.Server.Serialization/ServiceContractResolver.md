<Type Name="ServiceContractResolver" FullName="Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver">
  <TypeSignature Language="C#" Value="public class ServiceContractResolver : System.Net.Http.Formatting.JsonContractResolver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceContractResolver extends System.Net.Http.Formatting.JsonContractResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceContractResolver&#xA;Inherits JsonContractResolver" />
  <TypeSignature Language="F#" Value="type ServiceContractResolver = class&#xA;    inherit JsonContractResolver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Net.Http.Formatting.JsonContractResolver</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="020b1-101">既定値を表す<see cref="T:Newtonsoft.Json.Serialization.IContractResolver" />によって使用される<see cref="T:System.Net.Http.Formatting.JsonMediaTypeFormatter" />camel 形式のサポートの追加によりシリアル化、大文字と小文字がします。</span><span class="sxs-lookup"><span data-stu-id="020b1-101">Represents the default <see cref="T:Newtonsoft.Json.Serialization.IContractResolver" /> used by <see cref="T:System.Net.Http.Formatting.JsonMediaTypeFormatter" /> but with the addition of supporting camel cased serialization.</span></span> <span data-ttu-id="020b1-102">フォーマッタを使用して<see cref="T:System.Net.Http.Formatting.IRequiredMemberSelector" />必要なメンバーを選択し認識、<see cref="T:System.SerializableAttribute" />注釈を入力します。</span><span class="sxs-lookup"><span data-stu-id="020b1-102">It uses the formatter's <see cref="T:System.Net.Http.Formatting.IRequiredMemberSelector" /> to select required members and recognizes the <see cref="T:System.SerializableAttribute" /> type annotation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceContractResolver (System.Net.Http.Formatting.MediaTypeFormatter formatter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.Formatting.MediaTypeFormatter formatter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver.#ctor(System.Net.Http.Formatting.MediaTypeFormatter)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (formatter As MediaTypeFormatter)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver : System.Net.Http.Formatting.MediaTypeFormatter -&gt; Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver" Usage="new Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver formatter" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="formatter" Type="System.Net.Http.Formatting.MediaTypeFormatter" />
      </Parameters>
      <Docs>
        <param name="formatter"><span data-ttu-id="020b1-103"><see cref="T:System.Net.Http.Formatting.MediaTypeFormatter" />必要なメンバーを解決するために使用します。</span><span class="sxs-lookup"><span data-stu-id="020b1-103">The <see cref="T:System.Net.Http.Formatting.MediaTypeFormatter" /> used to resolve required members.</span></span></param>
        <summary>
            <span data-ttu-id="020b1-104">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver" />と、指定された<paramref name="formatter" />必要なメンバーを解決するのに使用します。</span><span class="sxs-lookup"><span data-stu-id="020b1-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver" /> with a given <paramref name="formatter" /> to use for resolving required members.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolvePropertyName">
      <MemberSignature Language="C#" Value="protected override string ResolvePropertyName (string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string ResolvePropertyName(string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Serialization.ServiceContractResolver.ResolvePropertyName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ResolvePropertyName (propertyName As String) As String" />
      <MemberSignature Language="F#" Value="override this.ResolvePropertyName : string -&gt; string" Usage="serviceContractResolver.ResolvePropertyName propertyName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
  </Members>
</Type>