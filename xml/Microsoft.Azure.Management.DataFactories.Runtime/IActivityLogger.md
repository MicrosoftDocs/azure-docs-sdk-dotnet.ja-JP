<Type Name="IActivityLogger" FullName="Microsoft.Azure.Management.DataFactories.Runtime.IActivityLogger">
  <TypeSignature Language="C#" Value="public interface IActivityLogger" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActivityLogger" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Runtime.IActivityLogger" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActivityLogger" />
  <TypeSignature Language="F#" Value="type IActivityLogger = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="53199-101">アクティビティの実行、ログ記録の機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="53199-101">Provides functionality for logging the execution of an activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public void Write (string format, params object[] args);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Write(string format, object[] args) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Runtime.IActivityLogger.Write(System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub Write (format As String, ParamArray args As Object())" />
      <MemberSignature Language="F#" Value="abstract member Write : string * obj[] -&gt; unit" Usage="iActivityLogger.Write (format, args)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="args" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="format"><span data-ttu-id="53199-102">複合書式設定文字列。</span><span class="sxs-lookup"><span data-stu-id="53199-102">A composite format string.</span></span></param>
        <param name="args"><span data-ttu-id="53199-103">書式設定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="53199-103">The objects to format.</span></span></param>
        <summary>
            <span data-ttu-id="53199-104">ログ アクティビティのメッセージ。</span><span class="sxs-lookup"><span data-stu-id="53199-104">Log activity message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>