<Type Name="IStorageAccess" FullName="Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess">
  <TypeSignature Language="C#" Value="public interface IStorageAccess" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStorageAccess" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStorageAccess" />
  <TypeSignature Language="F#" Value="type IStorageAccess = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bb521-101">HDInsight クラスターに対してジョブ操作のための記憶域アクセスの詳細を管理します。</span><span class="sxs-lookup"><span data-stu-id="bb521-101">Manages storage access details for job operations against HDInsight clusters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetFileContent">
      <MemberSignature Language="C#" Value="public System.IO.Stream GetFileContent (string file);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.IO.Stream GetFileContent(string file) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Job.Models.IStorageAccess.GetFileContent(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetFileContent (file As String) As Stream" />
      <MemberSignature Language="F#" Value="abstract member GetFileContent : string -&gt; System.IO.Stream" Usage="iStorageAccess.GetFileContent file" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="file" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="file">
            <span data-ttu-id="bb521-102">必須。</span><span class="sxs-lookup"><span data-stu-id="bb521-102">Required.</span></span> <span data-ttu-id="bb521-103">ダウンロードする必要があるファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="bb521-103">File path which needs to be downloaded.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bb521-104">入力ファイルの内容をメモリ ストリームとして取得します。</span><span class="sxs-lookup"><span data-stu-id="bb521-104">Gets the content of input file as memory stream.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bb521-105">ファイルの内容を含むメモリ ストリーム。</span><span class="sxs-lookup"><span data-stu-id="bb521-105">Memory stream which contains file content.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>